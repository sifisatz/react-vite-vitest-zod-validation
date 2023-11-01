<h1 align="center">Form validation demo 📝</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
</p>

> A demo of reading form data with serverside validation. Made possible by React and Netlify Serverless 🔹 

Source code from [Jason Lengstorf's eggheadio course](https://egghead.io/courses/create-a-typescript-powered-serverless-react-application-cf0acfbf) on Netlify serverless with TS + React.


## Install

```sh
npm install
```

## Serve locally

You'll need a copy of Netlify's CLI to run this project locally. I'd suggest installing this as a global dependency, and starting the dev server like so:

```sh
npm i -g netlify-cli
ntl dev
```

You should see the project at http://localhost:8888 🚀

## Run the test suites

You'll find 2 ways to run our test suites: [Jest](https://jestjs.io/) and [Vitest](https://vitest.dev/). I used this to compare each framework's up-front configuration costs, speed, and dev ergonomics. You'll find the same set of unit + integration tests written for each under:

```sh
tests/
  jest/ ...
  vitest/ ...
```

To see them in action, try running some of the following:

```sh
# Run jest in "watch" mode
npm run test:jest

# Run Vitest in "watch" mode
npm run test:vitest

# Run jest normally
npx jest

# Run Vitest normally
npx vitest run
```

## Author

👤 **Joseph Atzamis**

* Github: [@holben888](https://github.com/sifisatz)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_