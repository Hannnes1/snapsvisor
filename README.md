# Snapsvisor

A collection of Swedish snapsvisor, typeset in LaTeX as an A5 pamphlet.

## Downloading

A compiled PDF can be downloaded from the [Releases](https://github.com/Hannnes1/snapsvisor/releases) page.

## Printing

Generate a print-ready PDF using
[Bookbinder](https://momijizukamori.github.io/bookbinder-js/?customSigLength=0&flyleafs=0&sigFormat=booklet&rotatePage=true).

The link above has the correct settings for a duplex printer that flips on the
long edge. If your printer flips on the short edge, uncheck "Alternate Page
Rotation (AKA Flip on Long Side)". This has been tested on a Canon LBP6670dn.

## Building

To build the PDF from the LaTeX source, run

```
latexmk -pdf songs.tex
```

