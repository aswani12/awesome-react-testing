
![Awesome](https://camo.githubusercontent.com/13c4e50d88df7178ae1882a203ed57b641674f94/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f643733303566333864323966656437386661383536353265336136336531353464643865383832392f6d656469612f62616467652e737667)
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors)

# Awesome React Testing

A collection of React and React Native testing tools and strategies.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Unit Testing](#unit-testing)
  - [Jest](#jest)
    - [Fetch Mock](#fetch-mock)
  - [Other Frameworks](#other-frameworks)
  - [Assertion](#assertion)
  - [Runner](#runner)
- [Regression Testing](#regression-testing)
- [Blackbox Testing](#blackbox-testing)
- [Greybox Testing](#greybox-testing)
- [Linters](#linters)
  - [Regular](#regular)
  - [A11y](#a11y)
- [Maintence Managers](#maintence-managers)
- [Environment Helpers](#environment-helpers)
- [Performance](#performance)
- [Quality Checks](#quality-checks)
- [Coverage Reporting](#coverage-reporting)
- [Chaos Testing](#chaos-testing)
- [Production Checking / Testing](#production-checking--testing)
- [Audits](#audits)
- [Contributors](#contributors)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Tutorials

For web:

* [Testing React Components](https://www.valentinog.com/blog/testing-react/) - by Valentino Gagliardi
* [Fullstack React - Testing Chapter](https://www.fullstackreact.com/30-days-of-react/day-22/) - Day 22 of "30 Days of React"
* [Testing JavaScript with Kent C. Dodds](https://testingjavascript.com/) - Paid course 

For React Native:

* [Testing React Native Apps](https://jestjs.io/docs/en/tutorial-react-native) - Jest guide to React Native app testing

## Unit Testing

Choose one of these to be the primary framework you will be using to test your React and React Native apps. The most popular, by far, is Jest.

### Jest

Website: https://jestjs.io/
Works on projects using: Babel, TypeScript, Node, React, Angular, Vue and more.  Based on Mocha
Cheatsheet:  https://github.com/sapegin/jest-cheat-sheet

#### Fetch Mock

* [Jest Fetch Mock](https://github.com/jefflau/jest-fetch-mock) - Jest mock for the fetch polyfill.

More on Jest at [AWESOME-JEST](https://github.com/jest-community/awesome-jest)

### Other Frameworks

* [mocha](https://github.com/mochajs/mocha) - Simple, flexible, fun javascript test framework for node.js & the browser.
* [jasmine](https://github.com/jasmine/jasmine) - DOM-less simple JavaScript testing framework.
* [qunit](https://github.com/jquery/qunit) - An easy-to-use JavaScript Unit Testing framework.
* [prova](https://github.com/azer/prova) - Node & Browser test runner based on Tape and Browserify
* [DalekJS](https://github.com/dalekjs/dalek) - Automated cross browser functional testing with JavaScript
* [Protractor](https://github.com/angular/protractor) - Protractor is an end-to-end test framework for AngularJS applications.
* [tape](https://github.com/substack/tape) - Tap-producing test harness for node and browsers.
* [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing for the modern web development stack.
* [ava](https://github.com/avajs/ava) - 🚀 Futuristic JavaScript test runner
* [intern](https://github.com/theintern/intern) - A next-generation code testing stack for JavaScript.

### Assertion

Assertion libraries give you tools to ensure things are correct. For example, they may give you matchers such as `expect(true).toBeTruthy()`.

* [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
* [chai-immutable](https://github.com/astorije/chai-immutable)
* [Enzyme](http://airbnb.io/enzyme/index.html) - Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output.
* [react testing library](https://github.com/kentcdodds/react-testing-library) - Simple and complete React DOM testing utilities that encourage good testing practices.
  * [React Native Version](https://github.com/callstack/react-native-testing-library)
* [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs, and mocks for JavaScript.
* [expect.js](https://github.com/Automattic/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser.
* [React Unit](https://github.com/pzavolinsky/react-unit) - Lightweight unit test library for ReactJS
* [skin-deep](https://github.com/glenjamin/skin-deep) - Testing helpers for use with React's shallowRender test utils.
* [Unexpected React](https://github.com/bruderstein/unexpected-react/) - Plugin for [http://unexpected.js.org](http://unexpected.js.org/) to enable testing the full React virtual DOM.

### Browser-based Testing Tools

These allow you to run tests right in a real browser, to build full integration tests.

* [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit.
* [slimerjs](https://github.com/laurentj/slimerjs) - A PhantomJS-like tool running Gecko.
* [casperjs](https://github.com/casperjs/casperjs) - Navigation scripting & testing utility for PhantomJS and SlimerJS.
* [zombie](https://github.com/assaf/zombie) - Insanely fast, full-stack, headless browser testing using node.js.
* [totoro](https://github.com/totorojs/totoro) - A simple and stable cross-browser testing tool.
* [karma](https://github.com/karma-runner/karma) - Spectacular Test Runner for JavaScript.
* [nightwatch](https://github.com/nightwatchjs/nightwatch) - UI automated testing framework based on node.js and selenium webdriver.
* [yolpo](http://www.yolpo.com) - A statement-by-statement javascript interpreter in the browser.

## Snapshot Testing

These tools allow you to take "snapshots" of components and other data and verify that it remains the same between updates.

For web:

* [storyshots](https://github.com/storybooks/storybook/tree/next/addons)
* [testStateMachine in react-automata](https://github.com/MicheleBertoli/react-automata)

For React Native:

* [react-native-view-shot](https://github.com/gre/react-native-view-shot)


## Blackbox Testing

These tools allow you to write end-to-end integration tests -- without having any insight into the implementation details.

For React Native:

* [Appium](http://appium.io/)

## Greybox Testing

These tools are like the blackbox testing tools, except they integrate with internals of the web app to provide more consistency.

For web:

* [Cypress](https://www.cypress.io/)

For React Native:

* [Detox](https://github.com/wix/Detox)

## Linters and Formatters

Linters catch errors and protect against common problems. Formatters will reformat your code to ensure consistency.

### Linters

* [ESLint](https://github.com/eslint/eslint)
* [JSHint](https://github.com/jshint/jshint)
* [Standard](https://github.com/standard/standard)
* [Clinton](https://github.com/SamVerschueren/clinton)

### Formatters

* [Prettier](https://github.com/prettier/prettier)

### A11y (accessibility)

* [jsx-a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y)
* [react-native-a11y](https://github.com/FormidableLabs/eslint-plugin-react-native-a11y)

## Maintenance Managers

These tools automate tedious tasks like dependency upgrades.

* [DangerJS](https://github.com/danger/danger)
* [GreenKeeper.io](https://greenkeeper.io/)
* [Dependabot](https://dependabot.com/)
* [updtr](https://github.com/peerigon/updtr)
* [npm-check](https://github.com/dylang/npm-check)
* [Madge](https://github.com/pahen/madge)
* [Renovate](https://github.com/renovatebot/renovate)

## Environment Helpers

These packages help you verify that your environment matches the expected environment for the project (for example, Node versions, etc).

* [Solidarity](https://github.com/infinitered/solidarity)
* [EnvInfo](https://github.com/tabrindle/envinfo)

## Performance

Performance tools help you get the most speed out of your React and React Native apps.

For web:

* [Web Page Test](https://www.webpagetest.org/)
* [Insights](https://developers.google.com/speed/pagespeed/insights/)
* [BenchmarkJS](https://benchmarkjs.com/)

## Quality Checks

These tools will check for code quality scores.

* [JS Inspect](https://github.com/danielstjules/jsinspect)
* [buddy.js](https://github.com/danielstjules/buddy.js)

## Coverage Reporting

Coverage tools will alert you when you have untested code.

* [CodeCov](https://codecov.io/) - Coverage reporting service.
* [istanbul](https://github.com/gotwarlost/istanbul) - Yet another JS code coverage tool.
* [blanket](https://github.com/alex-seville/blanket) - A simple code coverage library for javascript. Designed to be easy to install and use, for both browser and nodejs.
* [JSCover](https://github.com/tntim96/JSCover) - JSCover is a tool that measures code coverage for JavaScript programs.

## Chaos Testing

Chaos testing ensures your tests are resilient to random data and interaction.

* [Psuedo-localization](https://github.com/tryggvigy/pseudo-localization)
* [Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings)
* [testcheck-js](https://github.com/leebyron/testcheck-js)
  * [Flow to testcheck](https://github.com/unbounce/babel-plugin-transform-flow-to-gen)

For web:

* [Service Fabric](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-testability-overview)
* [Gremlin](https://www.gremlin.com/)
* [Chaos Monkey](https://github.com/Netflix/chaosmonkey)

For React Native:

* [ClusterFuzz](https://github.com/google/clusterfuzz)

## Production Checking / Testing

These tools will allow you to see errors that happen in production apps.

For web:

* [Honeybadger](https://www.honeybadger.io/)
* [Errorception](https://errorception.com/)
* [Optimizely](https://www.optimizely.com/)

For mobile:

* [App Center](https://appcenter.ms)
* [Bug Snag](https://docs.bugsnag.com/platforms/react-native/)

## Audits

Auditing tools will give you information about your code structure.

* [jsx-info](https://www.youtube.com/watch?v=e_vtfYJW9aM&feature=youtu.be)

For web:

* [Lighthouse](https://www.w3.org/WAI/ER/tools/)


## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="http://gantlaborde.com/"><img src="https://avatars0.githubusercontent.com/u/997157?v=4" width="150px;" alt="Gant Laborde"/><br /><sub><b>Gant Laborde</b></sub></a><br /><a href="https://github.com/infinitered/awesome-react-testing/commits?author=GantMan" title="Documentation">📖</a></td><td align="center"><a href="https://jamonholmgren.com"><img src="https://avatars3.githubusercontent.com/u/1479215?v=4" width="150px;" alt="Jamon Holmgren"/><br /><sub><b>Jamon Holmgren</b></sub></a><br /><a href="#content-jamonholmgren" title="Content">🖋</a> <a href="#ideas-jamonholmgren" title="Ideas, Planning, & Feedback">🤔</a></td></tr></table>
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
