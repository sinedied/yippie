# yippie

[![NPM version](https://img.shields.io/npm/v/yippie.svg)](https://www.npmjs.com/package/yippie)
[![Build status](https://img.shields.io/travis/sinedied/yippie/master.svg)](https://travis-ci.org/sinedied/yippie)
![Node version](https://img.shields.io/badge/node-%3E%3D6.0.0-brightgreen.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> Extensible base generator and tools to chill out your Yeoman worflow

## Usage

This generator extends [Yeoman](https://yeoman.io) base generator with all the boilerplate needed to create complex template-driven generators, and even more.

First install the dependency:
```bash
npm install -S yippie
```

Then create a new generator like this:
```javascript
'use strict';
const Generator = require('yippie');
module.exports = Generator.make({ baseDir: __dirname });
```

Add some template files in a `templates/` folder and you're done.
 
Congratulations on making your first Yeoman generator! :tada:
