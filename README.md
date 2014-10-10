# Source Han Sans UTF-32 mappings for Japanese

[![Build Status](https://travis-ci.org/shinnn/source-han-sans-utf32-map-jp.svg?branch=master)](https://travis-ci.org/shinnn/source-han-sans-utf32-map-jp)

JSON version of 
[Source Han Sans][githubrepo] v1.000 UTF-32 mappings for Japanese

```javascript
{
  "(UTF-32 code point)": "(CID)"
  // ...
}
```

[**Download**](https://raw.githubusercontent.com/shinnn/source-han-sans-utf32-map-jp/master/source-han-sans-utf32-map-jp.json)

## Use as a JavaScript Library

[![NPM version](https://badge.fury.io/js/source-han-sans-utf32-map-jp.svg)](https://www.npmjs.org/package/source-han-sans-utf32-map-jp)
[![Bower version](https://badge.fury.io/bo/source-han-sans-utf32-map-jp.svg)](https://github.com/shinnn/source-han-sans-utf32-map-jp/releases)
[![Coverage Status](https://img.shields.io/coveralls/shinnn/source-han-sans-utf32-map-jp.svg)](https://coveralls.io/r/shinnn/source-han-sans-utf32-map-jp)
[![devDependency Status](https://david-dm.org/shinnn/source-han-sans-utf32-map-jp/dev-status.svg)](https://david-dm.org/shinnn/source-han-sans-utf32-map-jp#info=devDependencies)

### Installation

#### Package managers

##### [npm](https://www.npmjs.org/)

```sh
npm i --save source-han-sans-utf32-map-jp
```

##### [Bower](http://bower.io/)

```sh
bower i --save source-han-sans-utf32-map-jp
```

##### [Duo](http://duojs.org/)

```javascript
var sourceHanSansUtf32MapJp = require('shinnn/source-han-sans-utf32-map-jp');
```

#### Standalone

[Download the script file directly.](https://raw.githubusercontent.com/shinnn/scripts/source-han-sans-utf32-map-jp/master/scripts/source-han-sans-utf32-map-jp.js)

### API

#### sourceHanSansUtf32MapJp()

Return: `Object` (mapping data, same as the JSON file)

## Credit

The JSON file is generated from [the original data](http://sourceforge.net/projects/source-han-sans.adobe/files/Resources/) in [Source Han Sans project repository on SourceForge.net](http://sourceforge.net/projects/source-han-sans.adobe/).

### [Source Han Sans][githubrepo]

Licensed under [the Apache License, Version 2.0](https://github.com/adobe-fonts/source-han-sans/blob/master/LICENSE.txt)

## License

Copyright (c) 2014 [Shinnosuke Watanabe](https://github.com/shinnn)

Licensed under [the MIT License](./LICENSE).

[githubrepo]: https://github.com/adobe-fonts/source-han-sans/
