# QA Coding Challenge

Find three issues on Busbud.com and write the automated regression tests that reproduce the failure across one or more browsers.

## Functional requirements

* Tests are run on the command line using `npm test`
* Tests are run against a configurable host, with `www.busbud.com` as the default
* Tests can be configured to run various browser and OS combinations against a testing service (SauceLabs or BrowserStack), at a minimum the following should be included
  * IE10, Windows 8
  * Chrome latest, Windows 8
  * Safari latest, Mac OS latest
* Testing service credentials are passed as environment variables

## Non-functional requirements

* Tests are written in javascript, using NodeJS
* Tests are written against a BDD framework like `mocha`
* Tests cases describe expected behavior
* Style guide: https://github.com/busbud/js-style-guide

### Bonus

* Tests run against mobile browsers
* Tests capture screenshots of failures

## What we're looking for

1. Interesting or impactful issues
1. Using high-quality existing libraries or small amounts of custom code
1. Showing your work through your commit history
1. Polish
1. Pride in craftsmanship

## References

* https://docs.saucelabs.com/tutorials/node-js/
* http://www.browserstack.com/automate/node
