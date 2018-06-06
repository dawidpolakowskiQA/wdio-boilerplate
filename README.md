# UI test automation template

This project is to make starting with UI automation in your project as easy as possible. Please follow the steps below to enable WebDriverIO test automation for your project.

## Cloning this repo

Browse into your project's repository where you would like to introduce UI test automation. From there, use the command

```console
git submodule add --name <tests-folder-name> https://github.com/szarlatan/wdio-boilerplate
```

### Important

  `<tests-folder-name>` must be valid as a directory name and must not end with `/`

## Prerequisites

To run the tests on your local machine you need:

* [Java](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) 8
* [node](https://nodejs.org/en/) v.8.11.2 LTS (easiest way to manage node versions it to use [nvm](https://github.com/creationix/nvm#installation) on Unix-based OSes, or [nvm-win](https://github.com/coreybutler/nvm-windows#installation--upgrades) on Windows)
* [npm](https://www.npmjs.com/get-npm) v1.6.0
* [yarn](https://yarnpkg.com/en/docs/install#mac-stable) v1.7.0
* browsers required for testing

## Setup

If you meet the prerequisites listed above you can start setting up your project for the code and running.

* browse to the just cloned submodule folder
* run `yarn install` to fetch the packages and set yarn.lock file
* run `yarn wdio config` command to launch webdriverio config file wizard
  * always agree to fetch dependencies
  * for functional tests use mocha framework
  * for smoke tests use cucumber framework
  * recommended reporters are: `allure` and `spec`
  * recommended service is `selenium-standalone`