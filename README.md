#  TEST DRIVEN DEVELOPMENT

I use the Mocha framework for a tests.
```
$ npm install mocha -g
$ npm install chai
```
I add the --reporter=nyan option on the command line, then my test report features a flying rainbow space cat.
![happy cat](https://github.com/RaymondProduction/js-tdd-tutorial/raw/master/cat/01.png)
![sad cat](https://github.com/RaymondProduction/js-tdd-tutorial/raw/master/cat/02.png)
![cat](https://github.com/RaymondProduction/js-tdd-tutorial/raw/master/cat/03.png)
```
$ mocha --reporter=nyan <file of test>
```
To check was all the time
```
mocha --watch --reporter=nyan <file of test>
```
I use
```
mocha --watch --reporter=nyan ./*-spec.js

```

### Step 1. Getting started with unit tests
### Step 2. Working with network requests in TDD
