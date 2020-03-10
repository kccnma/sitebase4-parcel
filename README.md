# sitebase4-parcel
A SASS (SCSS) version of Sitebase, a minimal HTML + CSS + JS base front-end framework for simple web site projects, pre-setup and ready to be compiled via [Parcel]((https://parceljs.org/)).

[View demo](https://kccnma.github.io/sitebase4-parcel/)

## Install Instructions: 

1. Make sure you have Parcel installed globally. See (https://parceljs.org/) for docs. To install Parcel via yarn or npm:

* yarn:
```
    yarn global add parcel-bundler
```
* npm:
```
    npm install -g parcel-bundler
```
2. Create a package.json file in your project directory using:
```
    yarn init -y
```
* or
```
    npm init -y
```

## Dev instructions:
Run Parcel watcher:
```
parcel src/index.html
```
or
```
yarn run dev
```
or
```
npm run dev
```
Live reload should  initiate the project on http://localhost:1234. 

## Build instructions:

To build:
```
parcel build src/index.html
```
or
```
yarn run build
```
or
```
npm run build
```