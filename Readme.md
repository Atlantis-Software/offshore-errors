Offshore Errors
==========================

[![npm version](https://badge.fury.io/js/offshore-errors.svg)](https://www.npmjs.com/offshore-errors)
[![Build Status](https://travis-ci.org/Atlantis-Software/offshore-errors.svg?branch=master)](https://travis-ci.org/Atlantis-Software/offshore-errors)
[![Coverage Status](https://coveralls.io/repos/github/Atlantis-Software/offshore-errors/badge.svg?branch=master)](https://coveralls.io/github/Atlantis-Software/offshore-errors?branch=master)
[![NSP Status](https://nodesecurity.io/orgs/atlantis/projects/f5d848ca-b570-45f9-bdbb-e195480a989c/badge)](https://nodesecurity.io/orgs/atlantis/projects/f5d848ca-b570-45f9-bdbb-e195480a989c)
[![Dependencies Status](https://david-dm.org/Atlantis-Software/offshore-errors.svg)](https://david-dm.org/Atlantis-Software/offshore-errors)

A module for errors returned from offshore core, associations, and adapters. Each error module for a specific sub-system of offshore resides in `lib/modules`.

## Usage

```javascript
var Errors = require('offshore-errors');


function letsMakeAnError(options, cb) {
  var success = false;
  if (success) return cb();
  return cb(Errors.adapter.InvalidAuth);
}

```

## License (MIT)

Copyright (c) 2013-2014 Matt McFarland, Cody Stoltman & Balderdash Design Co.

Copyright (c) 2015 Atlantis Software.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
