# test-nightwatch-chrome-headless

> :ledger: Test project to setup Nightwatch.js (Selenium) + Chrome Headless

## Article

Explanation, how I've build this project is on [my blog][blog-post].

## How to run tests?

1. Installation of "nightwatch" and "selenium-standalone":

```bash
$ npm install  
```

2. Setup Selenium server (run daemon, so you should call at once):

```bash
$ npm run selenium:setup
```

3. (In another window) Use Nightwatch.js to launch integration tests:

```bash
$ npm run test:integration
```

## License

[The MIT License](http://piecioshka.mit-license.org) @ 2017


[blog-post]: https://piecioshka.pl/blog/2017/08/09/jak-napisac-testy-integracyjne-z-wykorzystaniem-nightwatch-oraz-chrome-headless.html

