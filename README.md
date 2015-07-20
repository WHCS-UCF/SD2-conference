# WHCS Senior Design II Conference Paper

The source files, build scripts, and source images with references for our
UCF Senior Design II conference paper.

For the work-in-progress, you may view the [latest build](/export/latest.pdf?raw=true)
There is also a [printable version](/export/latest-print.pdf?raw=true).

### Authors

Grant Hernandez | Jimmy Campbell | Joesph Love
:--------------:|:--------------:|:------------:
Computer Engineer | Computer Engineer | Electrical Engineer

Document typeset by Grant Hernandez using ViM with the help of writer2latex for Google Drive -> ODT -> TeX conversion.
All figures are the copyrights of the members of this group unless stated otherwise.
All trademarks of mentioned companies are referenced for educational purposes.

## Requirements
A working TeX distribution (i.e. MikTeX on windows or TeXLive on *nix), GNU
Make, and a working terminal.

## Workflow
Generating the document is as easy as typing `make`. You'll notice that the
document is built twice in order to pickup references.
This could be optimized to parse `pdflatex` output to
search for invalid reference hints.
