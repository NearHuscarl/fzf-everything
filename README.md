# Fzf everything

My collection of scripts to integrate fzf into everyday tasks.
Some of them is inspired from other people [works](https://github.com/NearHuscarl/fzf-everything#credit--related-works)

## Installation

Download the script and put it in `$PATH`

An exception is [sd](https://github.com/NearHuscarl/fzf-everything#change-directory-sd)

## Browser History

Search and open google chrome history in a new tab

#### Requirements
* google chrome
* fzf
* sqlite3

#### Demo

![chromhist](https://github.com/NearHuscarl/fzf-everything/blob/master/demo/history.gif)

## Open Files

Open file (default is to search in `$HOME`)

#### Requirements
* fzf
* ripgrep
* rifle (if you use xdg-open. add `OPEN=xdg-open` in ~/.bashrc)

#### Demo
![open](https://github.com/NearHuscarl/fzf-everything/blob/master/demo/open.gif)

## Manpage

Search manpages. Type `manfzf -u` to create and update cache and
`manfzf -c` to search in cache (slightly faster)

#### Requirements
* fzf
* vim (optional)

#### Demo
![man](https://github.com/NearHuscarl/fzf-everything/blob/master/demo/man.gif)

## Kill

End process. Default is kill (signal 9)

#### Requirements
* fzf

#### Demo
![open](https://github.com/NearHuscarl/fzf-everything/blob/master/demo/kill.gif)

## Change directory (sd)

cd meets fzf. `sd` means [s]earch [d]irectory

#### Requirements
* fzf
* fd

#### Setup
* Download [cd_fzf](https://github.com/NearHuscarl/fzf-everything/blob/master/cd_fzf)
* Add this line in ~/.bashrc: `source path/to/cd_fzf`

#### Demo
![sd](https://github.com/NearHuscarl/fzf-everything/blob/master/demo/sd.gif)

## Pacman

pacman + fzf

#### Requirements
* fzf
* pacman
* trizen (or other aur helper read from `$AUR_HELPER`)

#### Demo
![pacfzf](https://github.com/NearHuscarl/fzf-everything/blob/master/demo/pacfzf.gif)

## Downgrade

Downgrade package using pacman package manager

#### Requirements
* fzf
* pacman

#### Demo
![pacfzf](https://github.com/NearHuscarl/fzf-everything/blob/master/demo/downgrade.gif)


## Credit & Related Works
Some ideas or part of code is taken from:
* [Chrome History](https://github.com/junegunn/fzf/wiki/examples#browsing-history)
* [Kill](https://github.com/junegunn/fzf/wiki/examples#processes)
* [Downgrade](https://github.com/pbrisbin/downgrade)
* [Fzf examples](https://github.com/junegunn/fzf/wiki/examples)

## Licenses
**[BSD 3 Clauses](https://github.com/NearHuscarl/fzf-everything/blob/master/LICENSE.md)**
