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

### 1. Clone repository

```sh
clone git@github.com:Creatorise/teach-angular.git david-angular-introduction
cd david-angular-introduction # enter folder
```

### 2. Create Angular workspace

```sh
ng new client
# yes to routing and
# scss as stylesheet format

cd client
code .
```

### 3. Start Angular

-   Open a new terminal, then

```sh
npm start -- --open # in a new terminal
```

### 4. Create hello-world component

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
