# UI test automation template

This project is to make starting with UI automation in your project as easy as possible. Please follow the steps below to enable WebDriverIO test automation for your project.

## Cloning this repo

Browse into your project's repository where you would like to introduce UI test automation. From there, use the command

```console
git submodule add --name <tests-folder-name> https://bitbucket.org/ormlondon/<repo-path>
```

#### Important

  `<tests-folder-name>` must be valid as a directory name and must not end with `/`

## Prerequisites

To run the tests on your local machine you need:

* [Java](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) 8
* [node](#Installing-node) v.8.11.2 LTS+ (easiest way to manage node versions it to use [nvm](https://github.com/creationix/nvm#installation) on Unix-based OSes, or [nvm-win](https://github.com/coreybutler/nvm-windows#installation--upgrades) on Windows)
* [yarn](#installing-yarn)
* [selenium-standalone](#installing-selenium-standalone)
* browsers required for testing

### Installing node

With nvm tool it is really simple, just type:

* `nvm install --lts` on linux/mac
* `nvm install latest` on windows

If you still don't want to use **nvm/nvm-win** tool, you have to go to [node site](https://nodejs.org/en/), and install it following the instructions for your platform provided there.

### Installing yarn

yarn is a package manager, similar to npm, but way faster, providing dependency locking (so you won't face *strange, it works on my machine* issue anymore) and nice and smooth package upgrading mechanism. To install it go to project's [homesite](https://yarnpkg.com) and get the installation instructions for your platform.

### Installing selenium-standalone

## Setup