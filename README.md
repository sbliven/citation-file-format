[![Build Status](https://travis-ci.org/sdruskat/citation-file-format.svg?branch=master)](https://travis-ci.org/sdruskat/citation-file-format) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

# Citation File Format (CFF) - Documentation

Format specification for `CITATION` files. `CITATION` files provide reference and citation information for (research/scientific) software.

## This is the `documentation` branch

This branch holds the files to build a Jekyll site for GitHub Pages via Jekyll.

### Build

Build the specifications PDF with [the build script `build.sh`](https://github.com/sdruskat/citation-file-format/blob/master/build.sh).

Jekyll site build via Travis and [`build-jekyll.sh`](https://github.com/sdruskat/citation-file-format/blob/master/build-jekyll.sh).

## Create a new version / archive old versions

1. Create a directory for the current version as documented in `./index.md`. E.g., if the current version is 1.0.0, create a directory `1.0.0` and copy `./index.md` to that directory.
2. Set up `./index.md` for the new version by changing `version` in the metadata accordingly, e.g., tp `1.0.1`.
