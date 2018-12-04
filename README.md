# AutoDeb 

AutoDeb is an experimental script to completely automate compiling and
installing software. 

See https://wiki.ubuntu.com/AutoDeb

## This Repo

The source of autodeb.sh from the Ubuntu wiki is a pastebin. This repo
starts from the pastebin's contents and evolves with my personal
changes.

## Name Confusion

There is now another project named "autodeb" from Debian, which is
completely different! That project lives at https://auto.debian.org

## Installation

```
sudo apt-get install checkinstall auto-apt
sudo auto-apt update
sudo auto-apt updatedb && sudo auto-apt update-local
# TODO: curl down autodeb.sh into /usr/local/bin from this repo
```
