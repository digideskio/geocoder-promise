[![Build Status](https://travis-ci.org/DenisCarriere/geocoder-promise.svg?branch=master)](https://travis-ci.org/DenisCarriere/geocoder-promise)
[![Coverage Status](https://coveralls.io/repos/github/DenisCarriere/geocoder-promise/badge.svg?branch=master)](https://coveralls.io/github/DenisCarriere/geocoder-promise?branch=master)
[![npm version](https://badge.fury.io/js/geocoder-promise.svg)](https://badge.fury.io/js/geocoder-promise)

# Geocoder (ES6 Module)

A Geocoder written purely in TypeScript and returns Promises.

## Install

```bash
$ npm install --save geocoder-promise
```

## Quickstart

```javascript
import * as geocoder from 'geocoder-promise'

geocoder.google('New York City')
  .then(data => console.log(data))
```

![geocoder](https://cloud.githubusercontent.com/assets/550895/19335059/5482e9ca-90ce-11e6-993d-dc213a5084ad.gif)

## Tests

```bash
$ npm test
```

## Documentation

```bash
$ npm run docs
```

## Providers

| Providers       | Coverage    | Restrictions |
|-----------------|:------------|:-------------|
| Google          | Global      | API Key      |
