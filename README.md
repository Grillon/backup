# Backup tools

I'm trying to find a way to manage files on multiples computer and keep them safe. 

* I do not want to install huge tools. 
* I want to be able to manage unit small
* I want to be able to manage unit huge files
* I want to be able to manage directories

## Manage means 

* Control the number of copies
* Know where they are
* Backup / restore them localy and remotely
* Being able to view multiples generations

  It should be fast and easy to use

## candidates

* rsync + scripts
* dd + rsync + scripts
* git + dd + rsync + scripts
* bup
* git-annex

Don't like dup because it's hard to manage unit files.

## plan

Before scripting I would like to try bup and git-annex. They seems to correspond to what I search.

### how

1) try to reproduce an environment(for exemple a dev env) by saving and restoring critical files :

* Configurations files (/etc; .config; dotfiles and any special individuals conf files like eclipse.ini) 
* manually installed packages

I'll define everythings later.

2) try to save and restore documents with different kind of encoding iso-xxx & utf8(text, binaries, photos, videos)

try to save same files multiples times on differents point and generation.

I'll define that later too.

3) try to exchange files between computers, modify them and rebackup them.


