# Heroku Buildpack for Ghostscript

Installs Ghostscript 9.52 on Heroku

## Install

    $ cd /path/to/your-app
    $ heroku buildpacks:add https://github.com/ncr/heroku-buildpack-ghostscript.git

    # Push changes to deploy
    $ git push

    # This version of ghostscript will end up deployed at /app/vendor/ghostscript/bin/gs
