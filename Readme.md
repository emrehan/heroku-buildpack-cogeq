# Heroku Buildpack: COGEQ

This is the [Heroku buildpack](https://devcenter.heroku.com/articles/buildpacks) for [COGEQ](https://github.com/emrehan/cogeq)

Web processes must bind to `$PORT`, and only the HTTP protocol is permitted for incoming connections.

A `requirements.txt` file must be present under `server` directory and `COGEQ` must be included in `README.md`.
