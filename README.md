Heroku buildpack: Archive Team
==============================

This is a fun [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) that comes with wget-arc and rsync.

Usage
-----

Example usage:

    $ heroku create --stack cedar --buildpack http://github.com/kennethreitz/heroku-buildpack-archiveteam.git

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom buildpack
    -----> ArchiveTeam app detected
    -----> Fetching rsync
    -----> Fetching warc-get

