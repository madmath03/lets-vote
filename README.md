
<!--

Template variables to replace in ALL files:
* __app_name__: Name of the application
* __app_slug__: GitHub slug of the application
* __app_description__: Application description

After replacing all variables:
* Search for any [TODO] and do the required operations to complete your project documentation and CI/CD.

-->

[uri_license]: http://www.gnu.org/licenses/agpl.html
[uri_license_image]: https://img.shields.io/badge/License-AGPL%20v3-blue.svg

[![License: AGPL v3][uri_license_image]][uri_license]
[![Docs](https://img.shields.io/badge/Docs-Github%20Pages-blue)](https://monogramm.github.io/letsvote/)
[![gitmoji-changelog](https://img.shields.io/badge/Changelog-gitmoji-blue.svg)](https://github.com/frinyvonnick/gitmoji-changelog)
[![Managed with Taiga.io](https://img.shields.io/badge/Managed%20with-TAIGA.io-709f14.svg)](https://tree.taiga.io/project/monogrammbot-monogrammletsvote/ "Managed with Taiga.io")
[![Build Status](https://travis-ci.org/Monogramm/letsvote.svg)](https://travis-ci.org/Monogramm/letsvote)
<!--
[TODO] If project uses Coveralls for code coverage:

[![Coverage Status](https://coveralls.io/repos/github/Monogramm/letsvote/badge.svg?branch=master)](https://coveralls.io/github/Monogramm/letsvote?branch=master)
-->
<!--
[TODO] If project is deployed to DockerHub:

[![Docker Automated buid](https://img.shields.io/docker/cloud/build/monogramm/letsvote.svg)](https://hub.docker.com/r/monogramm/letsvote/)
[![Docker Pulls](https://img.shields.io/docker/pulls/monogramm/letsvote.svg)](https://hub.docker.com/r/monogramm/letsvote/)
[![Docker Version](https://images.microbadger.com/badges/version/monogramm/letsvote.svg)](https://microbadger.com/images/monogramm/letsvote)
[![Docker Size](https://images.microbadger.com/badges/image/monogramm/letsvote.svg)](https://microbadger.com/images/monogramm/letsvote)
-->
[![GitHub stars](https://img.shields.io/github/stars/Monogramm/letsvote?style=social)](https://github.com/Monogramm/letsvote)

# **Let's Vote**

> :alembic: A voting application project for mobile and web apps.

:construction: **This project is still in development!**

## :blue_book: Docs

See GitHub Pages at [monogramm.github.io/letsvote](https://monogramm.github.io/letsvote/).

## :chart_with_upwards_trend: Changes

All notable changes to this project will be documented in [CHANGELOG](./CHANGELOG.md) file.

This CHANGELOG is generated with :heart: by [gitmoji-changelog](https://github.com/frinyvonnick/gitmoji-changelog)
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## :bookmark: Roadmap

See [Taiga.io](https://tree.taiga.io/project/monogrammbot-monogrammletsvote/ "Taiga.io monogrammbot-monogrammletsvote")

## :construction: Install

```sh
composer install

yarn build

cp env.dist .env

docker-compose up -d

docker-compose exec phpfpm /app/bin/console doctrine:schema:create

add app.loc domain to your hosts file

access http://app.loc:8080 from your browser

```

## :rocket: Usage

```sh
access http://app.loc:8080 from your browser
```

## :white_check_mark: Run tests

```sh
echo "[TODO] Describe how to execute Unit Tests"
```

<!--
[TODO] If project is deployed to DockerHub:

## :whale: Supported tags

[Dockerhub monogramm/letsvote](https://hub.docker.com/r/monogramm/letsvote/)

* `latest`

-->

## :bust_in_silhouette: Authors

**Monogramm**

* Website: https://www.monogramm.io
* Github: [@Monogramm](https://github.com/Monogramm)

## :handshake: Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/Monogramm/letsvote/issues).
[Check the contributing guide](./CONTRIBUTING.md).<br />

## :thumbsup: Show your support

Give a :star: if this project helped you!

## :page_facing_up: License

Copyright © 2019 [Monogramm](https://github.com/Monogramm).<br />
This project is [AGPL v3](uri_license) licensed.

***
_This README was generated with :heart: by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
