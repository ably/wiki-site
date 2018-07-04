Wiki
====

This repository can be used to host a GitHub wiki

## Authentication

This app relies on Auth0 for authentication. See [`.env.example`](.env.example) for the environment variables needed. It is recommended you configure a Rule in Auth0 to limit authentication to a Google Apps domain.

## Running this locally

Copy [`.env.example`](.env.example) to `.env` and configure the environment variables if you want to use Auth0. Otherwise, add `AUTH_DISABLED=true` to `.env` to disable auth for local development.

`bundle`

Install the gems:

`bundle`

Build the static site:

`jekyll build`

Then run the server:

`rackup`

## Installation on Heroku

Configure the [environment variables](.env.example), and push the repo and that's it :)


Copyright (c) 2018 Ably Real-time Ltd, Licensed under the Apache License, Version 2.0. Refer to [LICENSE](LICENSE) for the license terms.
