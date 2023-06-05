# camarades.ch

This repository contains the source code for a website that will be published under [www.camarades.ch](https://www.camarades.ch). The website is built with [Hugo](https://gohugo.io/) and uses an adapted version of the [Hugo Whisper Theme](https://github.com/zerostaticthemes/hugo-whisper-theme).

## Structure of the repository

The repository consists of this main repository [crsuzh/camarades.ch](https://github.com/crsuzh/camarades.ch) and a sub-repository [crsuzh/hugo-whisper-theme](https://github.com/crsuzh/hugo-whisper-theme). The main repository contains, broadly speaking, the text contents of the website and its subpages whereas the sub-repository contains a fork of the original Hugo Whisper Theme.

## Cloning the repository

As this repository contains a submodule, you need to set the `--recurse-submodules` flag in the `git clone` command. Thus, the full command to clone the repository is:

`git clone --recurse-submodules git@github.com:crsuzh/camarades.ch.git`

if you are cloning via ssh, or

`git clone --recurse-submodules https://github.com/crsuzh/camarades.ch.git`

if you are cloning via https.

## Working with the repository

After cloning with one of the above commands, the submodule will be in detached HEAD state. This can be fixed by running the following commands:

```
cd camarades.ch/themes/hugo-whisper-theme
git checkout master
```

After that, everything should work as intended. Note, however, that if you make any changes to the submodule, i.e. to any file under `themes/hugo-whisper-theme`, you need to commit (and push) it from within the submodule directory. After committing these changes to the submodule, it is also necessary to update the reference to the submodule in the main repository.
