# camarades.ch

This repository contains the source code for a website that will be published under [www.camarades.ch](www.camarades.ch). The website is built with [Hugo](https://gohugo.io/) and uses an adapted version of the [Hugo Whisper Theme](https://github.com/zerostaticthemes/hugo-whisper-theme).

## Structure of the repository

The repository consists of this main repository [felix-hof/camarades.ch](https://github.com/felix-hof/camarades.ch) and a sub-repository [felix-hof/hugo-whisper-theme](https://github.com/felix-hof/hugo-whisper-theme). The main repository contains, broadly speaking, the text contents of the website and its subpages whereas the sub-repository contains a fork of the original Hugo Whisper Theme.

## Cloning the repository

As this repository contains a submodule, you need to set the `--recurse-submodules` flag in the `git clone` command. Thus, the full command to clone the repository is:

`git clone --recurse-submodules git@github.com:felix-hof/camarades.ch.git`

if you are cloning via ssh, or

`git clone --recurse-submodules https://github.com/felix-hof/camarades.ch.git`

if you ar cloning via https.

## Working with the repository

