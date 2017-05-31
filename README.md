# jquery-ui-pyritephp

[![GitHub release](https://img.shields.io/github/release/vphantom/jquery-ui-pyritephp.svg?style=plastic)]()

Minimal build of jQuery UI required for PyritePHP.

Upstream version: 1.12.1, built on 2017-05-31

Tailored for PyritePHP version: 1.2.4

## Build Details

* Components: Toggle All
* Interactions: check Sortable
* Theme: No Theme

## Usage

We primarily use this through Browserify, so requiring is all that's needed:

```js
'use strict';

var $ = global.jQuery = require('jquery');
require('jquery-ui-pyritephp');

...
```

File `jquery-ui.css` should also be included in your build process.

## LICENSE

Copyright jQuery Foundation and other contributors, https://jquery.org/

This software consists of voluntary contributions made by many individuals.  For exact contribution history, see the revision history available at https://github.com/jquery/jquery-ui

Full license details at https://github.com/jquery/jquery-ui/blob/master/LICENSE.txt
