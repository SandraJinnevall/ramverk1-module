SandraJinnevall/ramverk1-module
======================

[![Build Status](https://travis-ci.com/SandraJinnevall/ramverk1-module.svg?branch=master)](https://travis-ci.com/SandraJinnevall/ramverk1-module)
[![Build Status](https://scrutinizer-ci.com/g/iFaxity/SandraJinnevall/ramverk1-module/badges/build.png?b=master)](https://scrutinizer-ci.com/g/SandraJinnevall/ramverk1-module/build-status/master)
[![Code Coverage](https://scrutinizer-ci.com/g/SandraJinnevall/ramverk1-module/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/SandraJinnevall/ramverk1-module/?branch=master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/SandraJinnevall/ramverk1-module/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/SandraJinnevall/ramverk1-module/?branch=master)

## Installation

Instrallera genom att köra kommandot i mappen:

`composer require sandrajinnevall/ramverk1-module`

Lägg till följande rad i composer.json:

`"require": { "sandrajinnevall/ramverk1-module": "^1.0.5" }`

Lägg till filerna i rätt mapp genom att köra:

```bash
rsync -av vendor/sandrajinnevall/ramverk1-module/config/ ./
rsync -av vendor/sandrajinnevall/ramverk1-module/view/ ./
rsync -av vendor/sandrajinnevall/ramverk1-module/src/ ./
rsync -av vendor/sandrajinnevall/ramverk1-module/test/ ./
```
