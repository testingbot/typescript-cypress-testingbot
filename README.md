# cypress-typescript-testingbot

## Introduction

Cypress is a next generation front end testing tool built for the modern web. This example demonstrates how to run Cypress tests, written in Typescript, on [TestingBot](https://testingbot.com)
TestingBot is a cloud-based grid of browsers, ready to run your Cypress tests.

Simply specify the browsers you want to run the tests on. TestingBot will run the tests and generate a video, logs and screenshots of each Cypress test.

## Pre-requisites

You need a TestingBot key and secret to be able to run Cypress tests. You can get these for free at [TestingBot](https://testingbot.com).
Once you have these, either add them to the `testingbot.json` file, or export them as environment variables (these take precedence over the placeholders in `testingbot.json`):

```bash
export TESTINGBOT_KEY="your-testingbot-key"
export TESTINGBOT_SECRET="your-testingbot-secret"
```

## Run Cypress Typescript tests on TestingBot

1. Clone this repository
2. Install the dependencies using `npm install`
3. Run the sample using `npx testingbot-cypress run` (or `npm test`)

`testingbot-cypress-cli` is installed as a dev dependency, so call it through `npx`. A bare `testingbot-cypress run` only works if you installed the CLI globally (`npm install -g testingbot-cypress-cli`).

## Additional Resources

- View your test results on the [TestingBot dashboard](https://testingbot.com/members/)
- Documentation for writing [Test scripts in Cypress](https://testingbot.com/support/web-automate/cypress/tutorial)