# google-codelab-with-express

this project makes use of google codelab webcomponents and host it in ExpressJS.

The ExpressJS app is generated using [ExpressJS](https://expressjs.com/en/starter/generator.html) handlebar engine
```
express --view=hbs google-codelab-with-express
```

## setup

```
git clone git@github.com:jaricsng/google-codelab-with-express.git
npm install
bower install
```

when you have the following, choose 2
```
Unable to find a suitable version for test-fixture, please choose one by typing one of the numbers below:
    1) test-fixture#^1.0.0 which resolved to 1.1.2 and is required by codelab-components
    2) test-fixture#^3.0.0 which resolved to 3.0.0 and is required by web-component-tester#6.4.1

Prefix the choice with ! to persist it to bower.json

? Answer 2
```

## run it

```
DEBUG=google-codelab-with-express:* npm start
```

## view the codelab demo
```
http://localhost:3000/demo/codelab.html
```
