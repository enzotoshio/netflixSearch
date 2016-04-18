# NetSearch

Movies search using Netflix Roulette API.

## Installation

You need node v0.12.3, npm and mongo as a prerequisite.

### Run

Mongo:
```sh
$ mongo
$ use netflix
$ db.createCollection('user')
```

Sails:
```sh
$ sudo npm i -g sails
$ npm i
$ sails lift
```

### Test
Unit test - Karmajs:
```sh
$ npm i
$ npm i -g karma-cli
$ karma start
```

E2e tests - Protractor:
```sh
$ npm i -g protractor@1.8.0
$ webdriver-manager update
$ webdriver-manager start
$ protractor tests/e2e/config.js
```