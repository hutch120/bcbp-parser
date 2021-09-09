[![Build Status](https://travis-ci.org/cluny85/bcbp-parser.svg?branch=master)](https://travis-ci.org/cluny85/bcbp-parser)
[![Coverage Status](https://coveralls.io/repos/github/cluny85/bcbp-parser/badge.svg?branch=master)](https://coveralls.io/github/cluny85/bcbp-parser?branch=master)

# bcbp-parser
BCBP boarding pass code parser.

## Get Started

### Install

```
npm install bcbp-parser --save
```

## Usage

To use this lib, you have to import:

```javascript
const { parseBCBP } = require('bcbp-parser');
```

Check the test folder for use examples.

## TODO

- Fix Julian date to standard date
- Add implementation for security params

## IATA

Link to the BCBP standard: [BCBP-Implementation-Guide](https://www.iata.org/contentassets/1dccc9ed041b4f3bbdcf8ee8682e75c4/2021_03_02-bcbp-implementation-guide-version-7-.pdf)

## Contributing

Please read [CONTRIBUTING.md](https://github.com/cluny85/bcbp-parser/blob/master/CONTRIBUTING.md) for details on code of conduct, and the process for submitting pull requests.

## License

This project is licensed under the Apache License Version 2.0 - see the [LICENSE](LICENSE) file for details.
