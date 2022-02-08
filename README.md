![](https://img.shields.io/badge/Microverse-blueviolet)

# Hello Microverse Project

> A simple project to practice Linters and Gitflow.

## Built With

- HTML
- CSS
- Webhint
- Stylelint


## Getting Started

**This is an example of how you may give instructions on setting up your project locally.**
**Modify this file to match your project, remove sections that don't apply. For example: delete the testing section if the currect project doesn't require testing.**


To get a local copy up and running follow these simple example steps.

### Prerequisites
The basic requirements for building the executable are:

* VSCode or any other equivalent code editor
* node package manager

# Getting Started

#### Cloning the project
```
git clone  git@github.com:AdrianCSM/Hello-Microverse-Project.git 
```

## Getting packages and debuging with Stylelint
```
npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
```
##### For validation detection using Stylelint Run
```
npx stylelint "**/*.{css,scss}"
```
##### from parent source directory

## Getting packages and debuging with Webhint
```
npm init -y
npm install --save-dev hint@6.x
```
##### For validation detection using Webhint Run
```
npx hint .
```
##### from parent source directory

## 📝 License

This project is [MIT](./MIT.md) licensed.