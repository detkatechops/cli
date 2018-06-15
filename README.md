Heroku CLI
==========

![Heroku logo](https://d4yt8xl9b7in.cloudfront.net/assets/home/logotype-heroku.png)

[![Greenkeeper badge](https://badges.greenkeeper.io/heroku/cli.svg)](https://greenkeeper.io/)
[![Circle CI](https://circleci.com/gh/heroku/cli/tree/master.svg?style=svg)](https://circleci.com/gh/heroku/cli/tree/master)
[![Build status](https://ci.appveyor.com/api/projects/status/ouee3b9d7jwkjcr1/branch/master?svg=true)](https://ci.appveyor.com/project/Heroku/cli/branch/master)
[![CircleCI](https://circleci.com/gh/heroku/cli-macos-installer/tree/master.svg?style=svg&circle-token=90b3b4392dc1668e97108edabdfc2c6baddc3a17)](https://circleci.com/gh/heroku/cli-macos-installer/tree/master)
[![Snap Status](https://build.snapcraft.io/badge/heroku/cli.svg)](https://build.snapcraft.io/user/heroku/cli)
[![ISC License](https://img.shields.io/github/license/heroku/cli.svg)](https://github.com/heroku/cli/blob/master/LICENSE)
[![homebrew](https://img.shields.io/homebrew/v/heroku.svg)](https://github.com/Homebrew/homebrew-core/blob/master/Formula/heroku.rb)
[![npm](https://img.shields.io/npm/v/heroku.svg)](https://www.npmjs.com/package/heroku)

The Heroku CLI is used to manage Heroku apps from the command line. It is built using [oclif](https://oclif.io).

For more about Heroku see <https://www.heroku.com/home>

To get started see <https://devcenter.heroku.com/start>

Overview
========

This is the next generation Node-based Heroku CLI.  The goals of this project were to make plugins more flexible, remove Ruby as a runtime dependency, and make the CLI faster.

It has identical functionality to the old Ruby CLI. Under the hood, it is a modular CLI made up of node.js plugins.

For more on developing plugins, read [Developing CLI Plugins](https://devcenter.heroku.com/articles/developing-cli-plugins)

Issues
======

For problems directly related to the CLI, [add an issue on GitHub](https://github.com/heroku/cli/issues/new).

For other issues, [submit a support ticket](https://help.heroku.com/).

[Contributors](https://github.com/heroku/cli/contributors)

<!-- commands -->
# Command Topics

* [`heroku access`](docs/access.md) - manage user access to apps
* [`heroku addons`](docs/addons.md) - tools and services for developing, extending, and operating your app
* [`heroku apps`](docs/apps.md) - add yourself to an organization app
* [`heroku auth`](docs/auth.md) - check 2fa status
* [`heroku authorizations`](docs/authorizations.md) - OAuth authorizations
* [`heroku buildpacks`](docs/buildpacks.md) - display the buildpack_url(s) for an app
* [`heroku certs`](docs/certs.md) - a topic for the ssl plugin
* [`heroku ci`](docs/ci.md) - run an application test suite on Heroku
* [`heroku clients`](docs/clients.md) - OAuth clients on the platform
* [`heroku commands`](docs/commands.md) - list all the commands
* [`heroku config`](docs/config.md) - display the config vars for an app
* [`heroku container`](docs/container.md) - Use containers to build and deploy Heroku apps
* [`heroku domains`](docs/domains.md) - list domains for an app
* [`heroku drains`](docs/drains.md) - display the log drains of an app
* [`heroku dyno`](docs/dyno.md) - stop app dyno
* [`heroku features`](docs/features.md) - list available app features
* [`heroku git`](docs/git.md) - manage local git repository for app
* [`heroku help`](docs/help.md) - display help for heroku
* [`heroku keys`](docs/keys.md) - display your SSH keys
* [`heroku labs`](docs/labs.md) - disables an experimental feature
* [`heroku local`](docs/local.md) - run heroku app locally
* [`heroku logs`](docs/logs.md) - display recent log output
* [`heroku maintenance`](docs/maintenance.md) - display the current maintenance status of app
* [`heroku members`](docs/members.md) - manage organization members
* [`heroku notifications`](docs/notifications.md) - display notifications
* [`heroku orgs`](docs/orgs.md) - manage organizations
* [`heroku pg`](docs/pg.md) - manage postgresql databases
* [`heroku pipelines`](docs/pipelines.md) - list pipelines you have access to
* [`heroku plugins`](docs/plugins.md) - list installed plugins
* [`heroku ps`](docs/ps.md) - Client tools for Heroku Exec
* [`heroku psql`](docs/psql.md) - open a psql shell to the database
* [`heroku redis`](docs/redis.md) - manage heroku redis instances
* [`heroku regions`](docs/regions.md) - list available regions for deployment
* [`heroku releases`](docs/releases.md) - display the releases for an app
* [`heroku reviewapps`](docs/reviewapps.md) - disable review apps or settings on an existing pipeline
* [`heroku run`](docs/run.md) - run a one-off process inside a Heroku dyno
* [`heroku sessions`](docs/sessions.md) - OAuth sessions
* [`heroku spaces`](docs/spaces.md) - manage heroku private spaces
* [`heroku status`](docs/status.md) - status of the Heroku platform
* [`heroku teams`](docs/teams.md) - manage teams
* [`heroku update`](docs/update.md) - update the heroku CLI
* [`heroku webhooks`](docs/webhooks.md) - setup HTTP notifications of app activity
* [`heroku which`](docs/which.md) - show which plugin a command is in

<!-- commandsstop -->
