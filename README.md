# Heroku Buildpack Rarlab

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for adding rar and unrar command in your [Heroku](https://heroku.com) application.

## Multipacks

- More likely, you'll want to use it as part of a larger project, which needs to use rar and unrar command. The easiest way to do this is with a [multipack](https://github.com/heroku/heroku-buildpack-multi), where this is just one of the buildpacks you'll be working with. Follow commands below to get started.

        $ cat .buildpacks
        git://github.com/heroku/heroku-buildpack-python.git
        git://github.com/hasibulkabir/heroku-buildpack-rarlab.git

        $ heroku buildpacks:add https://github.com/heroku/heroku-buildpack-multi

### Another method

- Directly add this buildpack in your heroku app. Follow this command 👇 otherwise add from herou app settings.

        heroku buildpacks:add https://github.com/HasibulKabir/heroku-buildpack-rarlab

### Donation

- [PayPal](https://www.paypal.me/hasibulkabir)

### Copyright

- Copyright (C) 2019-2021 [Hasibul Kabir](https://github.com/HasibulKabir)
