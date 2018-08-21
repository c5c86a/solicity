[![Build Status](https://travis-ci.org/nicosmaris/solicity.svg?branch=master)](https://travis-ci.org/nicosmaris/solicity) [![Coverage Status](https://coveralls.io/repos/github/nicosmaris/solicity/badge.svg?branch=master)](https://coveralls.io/github/nicosmaris/solicity?branch=master)

A travis-ci script for solidity and web3.js

npm scripts:

1. `npm test` uses truffle to :

  1. compile the contracts folder
  2. run the test folder in a coverage-enabled fork of ganache-cli by solidity-coverage
  3. generate coverage report
