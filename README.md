# biblatex-lncs

BibLaTeX style for Springer Lecture Notes in Computer Science

## Introduction

The code works with `biblatex 2.2` and it requires `biber 1.2` as backend. It
extends the standard `BiBTeX` model by an `acronym` entry.

## Usage

```latex
\usepackage[backend=biber,
  style=lncs
]{biblatex}
```

## Status

I intend to maintain this fork and gladly accept pull requests and issues.

## Testing

For building the included `test.tex` the `llncs` class from the Springer author guidelines needs to be in scope. The CI can get it via the ENV variable `LLNCS_CLS`.

## License

Copyright (c) 2021 Merlin Göttlinger and contributors

Forked from <https://github.com/neapel/biblatex-lncs.git>,
who forked from <https://github.com/jossco/biblatex-lncs.git>, by Joseph Scott
who forked from <https://github.com/gvdgdo/biblatex-lncs.git>, by Guido Governatori

This package may be distributed under the terms of the LaTeX Project
Public License, as described in lppl.txt in the base LaTeX distribution.
Either version 1.0 or, at your option, any later version.
