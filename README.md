# Cryptokitties test

Code taken from the cryptokitties repository: https://github.com/cryptocopycats/awesome-cryptokitties

## Functions used

Used the basic functions to support the following features:

- Create Promo kitty
- Make kitty pregnant
- Transfer

## Changes made to the contracts in order to test

- Removed function access modifiers such as onlyCEO, onlyCTO ..
- Removed "external" function calling necessity for certain functions
- Removed "whenNotPaused" function access specifiers where required

## Relevant file added

[TestKittyCore.sol](https://github.com/blocktest-official/cryptokitties-test/blob/master/contracts/TestKittyCore.sol)

## Questions?

Feel free to contact contact@blocktest.net