# Contributing to iScroll / FAQ

You are very welcome to collaborate, all changes to the code will be released under an MIT license.

By submitting a pull request you implicitly agree to give rights of your code to the project authors. Your contribution will always be released under the same MIT license.

## Setting up the project

Navigate to the project's directory and install all dependencies with npm.

```
npm install
```

## Creating a build

Builds are created with `build.js`. Pass in which version of iScroll you want to build as arguments. 

```
> node ./build.js
Building release: iscroll

> node ./build.js lite infinite
Building release: lite
Building release: infinite

> node ./build.js dist # Builds all versions
Building release: lite
Building release: iscroll
Building release: zoom
Building release: probe
Building release: infinite
```
