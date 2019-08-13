## scontents — Stores LaTeX contents in memory or files
- Version: 1.1
- Date: 2019/08/12
- Author: Pablo González

## Description
The `scontents` package stores valid `LaTeX` code in memory (sequences) using the
`l3seq` module of `expl3`. The stored content (including verbatim) can be
used as many times as desired in the document, additionally can be written
to external files if desired.

## Requirements
The package requires the following packages:
- [filecontentsdef](https://ctan.org/pkg/filecontentsdef)
- [l3keys2e](https://ctan.org/pkg/l3keys2e)
- [xparse](https://ctan.org/pkg/xparse)

## Installation

The package `scontents` is present in `TeXLive` and `MiKTeX`, use the
package manager to install. For a manual installation, put `scontents.dtx` 
in your working directory and run `tex scontents.dtx`.

## License
The scontents package may be modified and distributed under the terms and
conditions of the [LaTeX Project Public License](https://www.latex-project.org/lppl/), version 1.3c or greater.

## Contents
- README.md (this file)
- scontents.pdf  (documentation)
- scontents.dtx  (master file that produced all files)
