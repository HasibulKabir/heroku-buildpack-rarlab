Heroku buildpack: heroku-buildpack-rarlab
======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
for adding rar and unrar to your application.

Multipacks
----------

More likely, you'll want to use it as part of a larger project, which needs to use rar and unrar. The easiest way to do this is with a [multipack](https://github.com/ddollar/heroku-buildpack-multi),
where this is just one of the buildpacks you'll be working with.

    $ cat .buildpacks
    git://github.com/heroku/heroku-buildpack-ruby.git
    git://github.com/hasibulkabir/heroku-buildpack-rarlab.git

    $ heroku buildpacks:add https://github.com/ddollar/heroku-buildpack-multi

By this you can use rar and unrar command.

### Another method
    heroku buildpacks:add https://github.com/HasibulKabir/heroku-buildpack-rarlab
