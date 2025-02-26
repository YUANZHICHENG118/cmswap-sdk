# batsoft swap SDK

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![Actions Status](https://github.com/batsoft/batsoft-sdk/workflows/CI/badge.svg)](https://github.com/batsoft/batsoft-sdk)
[![npm version](https://img.shields.io/npm/v/@batsoft/sdk/latest.svg)](https://www.npmjs.com/package/@batsoft/sdk/v/latest)
[![npm bundle size (scoped version)](https://img.shields.io/bundlephobia/minzip/@batsoft/sdk/latest.svg)](https://bundlephobia.com/result?p=@batsoft/sdk@latest)

In-depth documentation on this SDK is available at [batsoft.io](https://batsoft.io/docs/v2/SDK/getting-started/).

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/YUANZHICHENG118/batsoft-sdk.git
```

Move into the batsoft-sdk working directory

```sh
cd basoft-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
