# Heroku Buildpack: COGEQ

This is the [Heroku buildpack](https://devcenter.heroku.com/articles/buildpacks) for [COGEQ](https://github.com/emrehan/cogeq)

Web processes must bind to `$PORT`, and only the HTTP protocol is permitted for incoming connections.

A `requirements.txt` file must be present under `server` directory and `COGEQ` must be included in `README.md`.

## Using this buildpack

You can specify the Git URL of a buildpack when creating a new app:

    $ heroku create myapp --buildpack https://github.com/emrehan/heroku-buildpack-cogeq.git

You can change the buildpack for an existing app using the CLI:

    $ heroku buildpacks:set https://github.com/emrehan/heroku-buildpack-cogeq.git -a myapp
