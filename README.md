hgext
=====

Mercurial/HG convert plugin with a few new features

Purpose
=====
I wanted to have an option to convert hg repo with file mapping
without being history stripped.

Usage
=====
* hg convert --config convert.prefixempty=true --config convert.hg.allowempty=true --sourcesort --filemap ${FILEMAP} ${SRC} ${DEST}

Features
=====
* --config convert.hg.allowempty=true: Can save history under filemap enabled
* --config convert.hg.allowempty=true: Can produce empty commits if needed
* --config convert.prefixempty=true: Can prefix empty commits that were not skipped

Requirements (versions info)
=====
* python 2.7
* mercurial 2.7.1-2ppa1~raring1 (http://ppa.launchpad.net/tortoisehg-ppa/releases/ubuntu)
