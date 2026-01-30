# Diagram for the Andúril 2 UI

A one-page printable diagram for the
[Andúril 2](https://github.com/ToyKeeper/anduril) user interface for
flashlights by [ToyKeeper](https://github.com/ToyKeeper).

![Diagram for the Andúril 2 UI](https://github.com/dirtydancing/anduril-tikz-diagram/releases/latest/download/anduril-tikz-diagram.png "Andúril 2 UI")

## Download

Check the
[Releases](https://github.com/dirtydancing/anduril-tikz-diagram/releases).

The diagram releases correspond to ToyKeeper's Andúril 2 releases,
beginning with Andúril 2 release 2024-04-20. The respective diagram
release number starts with 01, for example 2024-04-20.01, and will be
incremented if changes are made. For recent changes, check the
[Changelog](CHANGELOG.md).

The file formats included in the diagram releases are:

- PDF - recommended for printing

- PNG - for on-screen viewing

- TEX - LaTeX source file

This is the standard, generic diagram, and I am focusing on this
diagram. There is also an exemplary model-specific
[diagram-0135](https://github.com/dirtydancing/anduril-tikz-diagram-0135)
available for
[model number](https://github.com/ToyKeeper/anduril/blob/trunk/MODELS)
0135, `hank-emisar-2ch` (for Andúril 2 release 2024-04-20 only).
In addition, you can check out an exemplary
[dark mode edition](https://github.com/dirtydancing/anduril-tikz-diagram-dark)
of this generic diagram (for Andúril 2 release 2025-07-07 only).

## Description

The diagram follows ToyKeeper's
[Andúril User Manual](https://github.com/ToyKeeper/anduril/blob/trunk/docs/anduril-manual.md).

It is created with [TikZ](https://github.com/pgf-tikz/pgf) for
[LaTeX](https://www.latex-project.org/). This leverages the flexibility
that LaTeX offers, and it produces a human-friendly source document, as
well as human-friendly Git diffs, because the TEX source file consists
of plain text.

To accommodate both Andúril newcomers and experienced users, the
brightness ramp takes center stage, literally in the center of the
page. From there, you can explore all the other features.

The diagram employs a few colors to facilitate orientation; you can
readily modify them in the TikZ code to suit your preferences. At the
same time, the diagram is designed to be printable with a black and
white printer.

## Instructions

The following instructions are valid for Linux, but can also serve as a
starting point for other operating systems.

To create TEX, PDF and PNG files, you need:

- To modify the TEX file: any text editor, such as
[GNOME Text Editor](https://apps.gnome.org/en/TextEditor/), which is
free software licensed under the
[GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html).

- To generate a PDF file from the TEX file: a TeX distribution, such as
[TeX Live](https://tug.org/texlive/), which is free software licensed
under [various licenses](https://tug.org/texlive/copying.html).

- To generate a PDF file from the TEX file: the
[Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3) font,
which is an open source font licensed under the
[SIL Open Font License](https://openfontlicense.org/).

To generate a PDF file from the TEX source file, open a terminal in the
folder of the TEX file and run 3 times:

`lualatex anduril-tikz-diagram.tex`

To convert the generated PDF file to a PNG file, run:

`pdftocairo -png -r 300 -singlefile anduril-tikz-diagram.pdf anduril-tikz-diagram`

## Credits

This diagram has been inspired by the works of:

- [containerfan](https://github.com/containerfan/anduril2-diagrams)

- [Lux-Perpetua](https://budgetlightforum.com/t/anduril-2-ui-diagrams-generic-lumintop-sofirn/65927) - on BLF

- [jameshome](https://github.com/jameshome/anduril-guide)

## Contributing

You are very welcome to contribute to the diagram. I appreciate that
the community is involved in the development of the Andúril flashlight
UI, and this diagram has been created in the same spirit.

- To contribute directly to the diagram, open a
[pull request](https://github.com/dirtydancing/anduril-tikz-diagram/pulls).

- To report a bug or to suggest an improvement, open an
[issue](https://github.com/dirtydancing/anduril-tikz-diagram/issues).

- To contribute in other ways, consider
[ToyKeeper's Patreon](https://www.patreon.com/ToyKeeper).
