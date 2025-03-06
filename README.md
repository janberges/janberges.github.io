# Documentation

To update the documentation of `XXX`, perform the following steps:

    cd /path/to/XXX/doc
    make
    rsync -av --delete html/ /path/to/io/XXX/
    cd /path/to/io
    git add --all
    git commit
    git push
