# Master Thesis Template

## Setup
1. Install the full TexLive distribution.
2. Install Biber.


## Citations
This template uses Biblatex.  To use a citation between parentheses, use
`\autocite` (for one citation) or `\autocites` (for more than one citation).
To use a citation in running text, use `\textcite`.  Change the citation style
in `document.sty`.  See the [Biblatex documentation][1] for more information.


## Subset of pages
To create a subset of pages (for review for example), install `stapler`.
The syntax is:

    stapler sel document.pdf 6-12 16 17-22 subset.pdf


## Dependencies
The template has the following direct package dependencies:

- [acronym](https://ctan.org/pkg/acronym) - Acronyms
- [amsmath](https://ctan.org/pkg/amsmath) - Mathematical typesetting
- [biblatex](https://ctan.org/pkg/biblatex) - Bibliographies
- [booktabs](https://ctan.org/pkg/booktabs) - Improved table quality
- [cleveref](https://ctan.org/pkg/cleveref) - Intelligent cross-referencing
- [color](https://ctan.org/pkg/color) - Color management
- [csquotes](https://ctan.org/pkg/csquotes) - Context-sensitive quotes
- [fontspec](https://ctan.org/pkg/fontspec) - Advanced font selection
- [graphicx](https://ctan.org/pkg/graphicx) - Enhanced include-graphics support
- [hyperref](https://ctan.org/pkg/hyperref) - Hypertext support
- [listings](https://ctan.org/pkg/listings) - Code listings
- [mathabx](https://ctan.org/pkg/mathabx) - Mathematical symbols
- [microtype](https://ctan.org/pkg/microtype) - Improved text justification
- [sourcecodepro](https://ctan.org/pkg/sourcecodepro) - Source Code Pro font
- [tabularx](https://ctan.org/pkg/tabularx) - Tables with adjustable-width columns
- [todonotes](https://ctan.org/pkg/todonotes) - TODO notes
- [wrapfig](https://ctan.org/pkg/wrapfig) - Text flows around figures
- [xargs](https://ctan.org/pkg/xargs) - Define commands with many optional arguments
- [xassoccnt](https://ctan.org/pkg/xassoccnt) - Counters
- [xcolor](https://ctan.org/pkg/xcolor) - Color extensions
- [xltxtra](https://ctan.org/pkg/xltxtra) - Latex extras
- [xunicode](https://ctan.org/pkg/xunicode) - Unicode support



[1]: http://ctan.triasinformatica.nl/macros/latex/contrib/biblatex/doc/biblatex.pdf