# js-jest-pkg-starter
[![npm](https://img.shields.io/npm/v/js-jest-pkg-starter.svg)](https://www.npmjs.com/package/js-jest-pkg-starter)
[![Build Status](https://travis-ci.com/briwa/js-jest-pkg-starter.svg?branch=master)](https://travis-ci.com/briwa/js-jest-pkg-starter)
[![Coverage Status](https://coveralls.io/repos/github/briwa/js-jest-pkg-starter/badge.svg?branch=master)](https://coveralls.io/github/briwa/js-jest-pkg-starter?branch=master)
![Snyk Vulnerabilities for GitHub Repo](https://img.shields.io/snyk/vulnerabilities/github/briwa/js-jest-pkg-starter.svg)


For those of you who wanted to create a quick, simple npm package in Javascript.

What's included in this starter pack:
- Javascript (Babel)
- Jest
- Travis CI
- Coveralls
- A very opinionated linting rule `standard`, feel free to change/remove this under `.eslintrc.js` to suit your own linting rules

## Getting started
- Clone this repo
- Write your own code and modify as needed
- ???
- Profit!

## Running tests
```bash
npm run test # Without coverage
npm run test -- --coverage # With coverage
```

## Build
```bash
npm run build # For production, outputs to ES5
```