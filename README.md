Git Coreutils
=============

Coreutils for Git repository. They work on bare repository.

Installation
------------

Put them all into any directory in PATH. e.g.) /usr/bin

Usages
------

#### git-cp

Copy `foo.txt` and `bar.txt` into `/path/to/dest` in bare repository `repo.git`

    $ git cp foo.txt bar.txt repo.git/path/to/dest

Copy `foo.txt` into `/path/to/dest` as `bar.txt` in bare repository `repo.git`

    $ git cp foo.txt repo.git/path/to/dest/bar.txt

#### git-cat

    $ cd <repo.git>
    $ git cat <filename>

Dependency
----------

* Python

TODO
----

* git-mv
* git-rm