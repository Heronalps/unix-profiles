# My Unix Profiles

After looking at [amix/vimrc](https://github.com/amix/vimrc), I was inspired to create some sort of version controlled copy of all of my unix/terminal 
settings. With this approach, all of my favorite settings can be recorded and maintained beyond the scope of a single computer. So if I ever need to set
myself up on a new system (a highly likely event), I can clone this repository and have an instantly familiar working environment!

*NOTE*: This is actually a fork of [amix/vimrc](https://github.com/amix/vimrc) that I modified for my own use. All credits for the vimrc part of things should
go to [amix](https://github.com/amix) and the collaborators on that repo.

## Installing vimrc

First, clone this repository wherever you like and cd into it.

```bash
~/github/ $ git clone git@github.com:ncbrown/profiles.git
~/github/ $ cd profiles/
~/github/profiles/ $ ln -s ~/github/profiles/vimrc ~/.vim_runtime
~/github/profiles/ $ cd ~/.vim_runtime
~/.vim_runtime/ $ bash install_awesome_vimrc.sh
```

## Inspirations

* .vimrc from [amix/vimrc](https://github.com/amix/vimrc) because it is well structured, useful, and pretty
* Homebrew from [brew.sh](http://brew.sh) because every developer needs Homebrew
