# node-email-validation
A email validation package for NodeJS. A simple module to validate an e-mail address.

[![travis build](https://img.shields.io/travis/manishsaraan/node-email-validation.svg?style=flat-square)](https://travis-ci.org/manishsaraan/node-email-validation)
[![version](https://img.shields.io/npm/v/node-email-validation.svg?style=flat-square)]((http://npm.im/node-email-validation))
[![downloads](https://img.shields.io/npm/dm/node-email-validation.svg?style=flat-square)](https://npm-stat.com/charts.html?package=node-email-validation&from=2019-08-28)
[![size](https://img.shields.io/spiget/download-size/2?color=green&style=flat-square)](https://img.shields.io/spiget/download-size/2?color=green&style=flat-square)

## Installation
Install via NPM:

```bash
npm install node-email-validation

```

## Usage

#### javascript

```javascript

var validator = require("node-email-validation");

validator.is_email_valid("test@email.com"); // true

```

#### TypeScript

```typescript

import * as EmailValidator from 'node-email-validation';

EmailValidator.is_email_valid("test@email.com"); // true


```

Yes, it's really all you need to get started as you can see in this live and interactive demo:

[![Edit Button](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/embed/recursing-dubinsky-vszmz)

## Questions

For *how-to* questions and other non-issues,
please use [StackOverflow](https://stackoverflow.com/search?q=node-email-validation) instead of Github issues.
There is a StackOverflow tag called "node-email-validation" that you can use to tag your questions.



## Contributing

We'd greatly appreciate any [contribution](/CONTRIBUTING.md) you make. :)


## License

This project is licensed under the terms of the
[MIT license](/LICENSE).


