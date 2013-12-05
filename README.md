hgext
=====

Mercurial/HG convert plugin with a few new features

Purpose
=====
I wanted to have an option to convert hg repo with file mapping
without being history stripped.

Features
=====
* Can save history under filemap enabled
* Can produce empty commits if needed
* Can prefix empty commits that were not skipped

Requirements (versions info)
=====
* python 2.7
* mercurial 2.7.1-2ppa1~raring1 (http://ppa.launchpad.net/tortoisehg-ppa/releases/ubuntu)
