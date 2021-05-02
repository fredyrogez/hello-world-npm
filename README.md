# hello-world-npm

A simple example NPM package.

## Installation
```
$ npm install @rgz/hello-world-npm
```

## Usage
```
const hello = require('@rgz/hello-world-npm');
hello.printHelloWorld();
```

## Creating and publishing your package

#### 1. Create a directory for your package : ####
```
$ mkdir my-package
```

#### 2. Navigate into package directory : ####
```
$ cd my-package
```

#### 3. If you are using github to manage your package code : ####
```
$ git init
$ git remote add origin https://github.com/user/repo.git
```

#### 4. Set up your NPM package (create a package.json) : ####
```
$ npm init
```

#### 5. Write the code ! ####

#### 6. Dont forget to create the README.md file. ####

#### 7. Login to NPM : ####
```
$ npm login
```

#### 8. Publish your package to the NPM registry : ####
```
$ npm publish
```

**That's all folks !**
