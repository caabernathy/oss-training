# CONTRIBUTING

Contributions are always welcome, no matter how large or small. Before contributing, please read the [code of conduct](CODE_OF_CONDUCT.md).

## Pull Requests

We actively welcome your pull requests.

1. Fork the repo and create your branch from `master`.
1. If you've added code that should be tested, add tests and make sure the test suite passes.
1. If you've made documentation fixes, we love you!

## Testing Code Changes

If you make code changes, we expect you to detail how you tested the changes when your submit the pull request.

You can send a link to a [JSFiddle](https://jsfiddle.net/) where you show a working test. Here's an example fiddle showing [add functionality](https://jsfiddle.net/j6Leyhg3/).

If you add new functionality, we expect you to add a new test in the `js/__tests__` folder. These are [Jest](http://facebook.github.io/jest/) tests. See existing tests as examples.

If you're not familiar with Jest, and/or you aren't ready to install it, just add a test anyway. The reviewer will run your test to make sure it passes.

Alternatively, you can set up Jest and get brownie points for mentioning in the pull request that you've run the local test suite.

**Jest testing setup**

You only need to do the following one time:

1. Install [Brew](http://brew.sh/)
1. Install Node
```sh
brew install node
```
1. Install Watchman
```sh
brew install watchman
```
1. Install Yarn
```sh
npm install -g yarn
```


Go to the top-level folder for this repository on your machine and run the following command:

```sh
yarn install
```

**Running Jest tests**

In your top-level folder, run the following whenever you want to test your changes:

```sh
yarn test
```
You should see something similar to the following:

```sh
$ yarn test
Using globally installed version of Yarn
yarn test v0.21.2
$ jest
 PASS  js/__tests__/sum.test.js
  ✓ adds 1 + 2 to equal 3 (2ms)

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   0 total
Time:        0.816s, estimated 1s
Ran all test suites.
✨  Done in 1.68s.
```

Expect to see more tests listed as more tests are added.



## License

By contributing to this project, you agree that your contributions will be licensed under its [MIT license](LICENSE).
