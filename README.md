# Python package documentation

To update the documentation of package `XXX`, perform the following steps:

    cd /path/to/XXX/doc
    make
    rsync -av --delete html/ /path/to/io/XXX/
    cd /path/to/io
    git add -u
    git commit --amend
    git push -f

Since the content of this repository is generated automatically with Sphinx and
Groff, no commit history is necessary and we can just overwrite the previous
commit with `git push -f`.
