# Introduction to Angular and ag-Grid

## Before we start

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
cd david-angular-introduction # enter folder
```

### 2. Create Angular workspace

```sh
ng new country-table
# yes to routing and
# scss as stylesheet format
```

### 3. Create hello-world component

```sh
cd country-table

ng generate component hello-world --skip-tests
# or
ng g c hello-world --skip-tests
```

## Project teardown

```sh
rm david-angular-introduction -rf
npm uninstall @angular/cli
```
