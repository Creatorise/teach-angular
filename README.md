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
ng new david-angular-introduction
# yes to routing &
# scss as stylesheet format
# Or
ng new david-angular-introduction --skip-git --skip-tests --routing true --style scss

cd david-angular-introduction
code .
```

### 2. Start Angular

-   Open a new terminal, then

```sh
npm start -- --open # in a new terminal
```

### 3. Create hello-world component

```sh
ng generate component hello-world
# or
ng g c hello-world
```

## Project teardown

```sh
rm david-angular-introduction -rf
npm uninstall @angular/cli
```
