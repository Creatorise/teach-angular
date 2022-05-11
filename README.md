# Introduction to Angular

## Before we start

-   Installed nodejs
-   Installed npm

## Install Angular-cli

```sh
npm install -g @angular/cli
```

[_Local setup guide_](https://angular.io/guide/setup-local)

## Getting started

### 1. Create Angular workspace

```sh
ng new angular-introduction
# yes to routing &
# scss as stylesheet format

# Or instead
ng new angular-introduction --skip-git --skip-tests --routing true --style scss

cd angular-introduction
code .
```

### 2. Start Angular

#### Option A - Run in vscode

-   Open run and debug tab
-   Run `ng serve`

#### Option B - From a new terminal

```sh
npm start -- --open # (in a new terminal)
```

### 3. Create hello-world component

```sh
ng generate component hello-world
# or
ng g c hello-world
```

## Project teardown

```sh
rm angular-introduction -rf
npm uninstall @angular/cli
```
