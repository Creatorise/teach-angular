# Introduction to Angular and ag-Grid

# Before we start

-   Installed nodejs
-   Installed npm

## Install Angular-cli

```sh
npm install -g @angular/cli
```

[Angular local setup guide (https://angular.io/guide/setup-local)](https://angular.io/guide/setup-local)

## Getting started

### 1. Clone repository

```sh
clone git@github.com:Creatorise/teach-angular.git david-angular-introduction
cd david-angular-introduction # Enter folder
```

### 2. Create Angular workspace

```sh
ng new country-table --minimal --skip-git --routing false --style scss
# OR
ng new country-table --interactive
```

## Project teardown

```sh
rm -rf david-angular-introduction
npm uninstall @angular/cli
```
