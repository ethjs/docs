<img src="https://raw.githubusercontent.com/ethjs/docs/master/assets/ethjs-image.png" width="250" />

## Welcome

Welcome to `ethjs`, a simple set of modules and examples for the Ethereum ecosystem.

## About

`ethjs` is a set of tiny composable modules and interfaces for the Ethereum ecosystem.

## Experimental

Note, all `ethjs` modules are highly experimental. If you want to bring `ethjs` into production use, please help out, and start user testing `ethjs`!

We are aiming for **early January 2017** for production use.

## Web3.js

We love `web3.js`! [`web3.js`](https://github.com/ethereum/web3.js) has brought us a first pass at a library for building Ethereum dApps and apps. We hope to work closely with the developers and maintainers of web3 to foster better design, share knowledge and give alternative design insight.

However, there are some critical differences between `ethjs` and `web3.js`:
  - `ethjs` has no support for decimal numbers [read more](https://github.com/ethjs/ethjs/blob/master/docs/user-guide.md#big-numbersnumber-handling)
  - `ethjs` uses **BN.js**, not `BigNumber.js` [read more](https://github.com/ethjs/ethjs/blob/master/docs/user-guide.md#big-numbersnumber-handling)
  - `ethjs` is **async only** for all RPC/data packet methods
  - `ethjs` uses `Buffer.js` for handling of hex/utf-8 conversion
  - `ethjs` is highly optimized for the browser (about **30kb** smaller than web3.js minified)
  - `ethjs` has a module first approach, small isolated modules which make up the complex whole
  - `ethjs` is **ES6+ first**, published with **ES5** standard via `babel`
  - `ethjs` has a **100% build uptime/+99% coverage** policy across all repos
  - `ethjs` is designed with **high configurability** at every level of each module
  - `ethjs` has a fail loudly, early (preferably within async) policy
  - `ethjs` has an enforced [UNIX philosophy](https://en.wikipedia.org/wiki/Unix_philosophy) design policy

## Heads Up

Note, all `ethjs` modules may eventually be merged into the `ethereumjs` Github org. We are currently in discussions to find the best path forward for these modules.

## Relationship with [`ethereumjs`](https://github.com/ethereumjs)

`ethjs` is a set of modules that are part of the EthereumJS community. We dedicate all these modules to the javascript developers of the Ethereum community in the hopes that they might be useful for dApps, apps and developers.

While we have no official affiliation with the Ethereum foundation, we will be working closely with the Ethereum community.

Please visit, [github.com/ethereumjs](https://github.com/ethereumjs) for more.

## Contributing

Please help better the ecosystem by submitting issues and pull requests to `ethjs`. We need all the help we can get to build the absolute best linting standards and utilities. We follow the AirBNB linting standard and the unix philosophy.

## Guides

You'll find more detailed information on using `ethjs` and tailoring it to your needs in our guides:

- [User guide](https://github.com/ethjs/ethjs/blob/master/docs/user-guide.md) - Usage, configuration, FAQ and complementary tools.
- [Developer guide](https://github.com/ethjs/ethjs/blob/master/docs/developer-guide.md) - Contributing to `ethjs` and writing your own code and coverage.
- [Examples](http://github.com/ethjs/examples) - Examples of `ethjs` in use.

## Module Guide

Here is a map of the `ethjs` modules with a brief explanation of each.

#### Interfaces
 - [ethjs](http://github.com/ethjs/ethjs) - a simple interface of various modules

#### Querying/RPC
 - [ethjs-query](http://github.com/ethjs/ethjs-query) - a module for querying the RPC layer with payload formatting
 - [etjs-rpc](http://github.com/ethjs/ethjs-rpc) - a module for querying the RPC layer without formatting

#### Providers
 - [ethjs-provider-signer](http://github.com/ethjs/ethjs-provider-signer) - sign raw transactions at the provider level
 - [ethjs-provider-http](http://github.com/ethjs/ethjs-provider-http) - a basic http provider

#### Unit Conversion
 - [ethjs-unit](http://github.com/ethjs/ethjs-unit) - convert between units such as `ether` and `wei`

#### Formatting
 - [ethjs-format](http://github.com/ethjs/ethjs-format) - payload formatter for the Ethereum RPC layer
 - [ethjs-schema](http://github.com/ethjs/ethjs-schema) - the entire Ethereum RPC schema as a JSON object
 - [ethjs-abi](http://github.com/ethjs/ethjs-abi) - Solidity transaction formatting

#### Filtering/Events
 - [ethjs-filter](http://github.com/ethjs/ethjs-filter) - filter and event handling for Ethereum RPC filters

#### Contract Handling
 - [ethjs-contract](http://github.com/ethjs/ethjs-contract) - a contract object abstraction

#### Transaction Signing
 - [ethjs-signer](http://github.com/ethjs/ethjs-signer) - a raw transaction signer

#### Accounts
 - [ethjs-account](http://github.com/ethjs/ethjs-account) - a module for creating and managing Ethereum accounts

#### Utils
 - [ethjs-util](http://github.com/ethjs/ethjs-util) - simple utils mainly for handling strings and hex values

## Help out

There is always a lot of work to do, and will have many rules to maintain. So please help out in any way that you can:

- Create, enhance, and debug ethjs rules (see our guide to ["Working on rules"](./.github/CONTRIBUTING.md)).
- Improve documentation.
- Chime in on any open issue or pull request.
- Open new issues about your ideas for making `ethjs` better, and pull requests to show us how your idea works.
- Add new tests to *absolutely anything*.
- Create or contribute to ecosystem tools.
- Spread the word!

Please consult our [Code of Conduct](CODE_OF_CONDUCT.md) docs before helping out.

We communicate via [issues](https://github.com/ethjs/ethjs/issues) and [pull requests](https://github.com/ethjs/ethjs/pulls).

## Important documents

- [Code of Conduct](CODE_OF_CONDUCT.md)
- [License](https://raw.githubusercontent.com/ethjs/ethjs/master/LICENSE)

## Special Thanks

`ethjs` was built by a strong community of Ethereum developers. A special thanks to:

- [Fabian Vogelsteller](https://twitter.com/feindura?lang=en) - for his work on `Mist` and `web3.js`
- [Tim Coulter](https://github.com/tcoulter) - for his work on `TestRPC` and `Truffle`
- [Aaron Davis](https://github.com/kumavis) - for his guidence and work on `MetaMask` and `ethereumjs`
- [Richard Moore](https://github.com/ricmoo) - for his work on `ethers-io` and `ethers-wallet` from which so much of `ethjs` is build from
- [Karl Floersch](https://twitter.com/karl_dot_tech?lang=en) - for his guidence and support
- [Martin B.](https://github.com/wanderer) - for his work on `ethereumjs`
- [Alex Beregszaszi](https://github.com/axic) - for his work on `ethereumjs`
- [Vitalik Buterin](https://twitter.com/VitalikButerin) - for creating `Ethereum`
