# TDD Katas

List of exercises to practice TDD.

## Katas

- [FizzBuzz](./FizzBuzz/README.md)
- [Credit Card Flag](./CreditCardFlag/README.md)
- [Roman Numerals](./RomanNumerals/README.md)

## Getting started

You can use **any programming language** to exercise TDD.

When in doubt, you can use JavaScript. For this you need to have [Node.js](https://nodejs.org/) installed, and then you can run the following command in the root of this repository:

```bash
npm init --yes
```

This will generate the `package.json` file, now you can install [Jest](https://jestjs.io/):

```bash
npm install jest
```

Change the test script in `package.json` to make it easier to run the tests:

```diff
-    "test": "echo \"Error: no test specified\" && exit 1"
+    "test": "jest --watch"
```

Now just run the tests:

```bash
npm test
```

Jest will watch for any changes to the project and trigger the tests, this will make the TDD cycle more productive.

Use the `*.test.js` extension for Jest to recognize it as a test file.

## Contributing

Every new Kata is welcome, just make the Pull Request or request through an issue.

Don't send the problem resolution, Kata's goal is not to solve the problem, it's to practice TDD. If you want to record the resolution, fork this repository and commit to a secondary branch, so you can keep the `main` branch intact to push new Katas to this repository 😉.
