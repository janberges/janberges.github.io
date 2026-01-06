# Documentation

To update the documentation of `XXX`, perform the following steps:

    cd /path/to/XXX/doc
    make
    rsync -aLv --delete html/ /path/to/io/XXX/
    cd /path/to/io
    git add --all
    git commit
    git push

The website is mirrored here:

* <https://io.janberges.de>
* <https://janberges.github.io>
* <https://berges.bitbucket.io>
