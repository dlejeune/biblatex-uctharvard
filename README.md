# UCT Author-Year Style For BibLaTeX

Preamble commands that extend the inbuilt `authoryear` style from BibLaTeX to support UCT's [flavour of Harvard referencing](http://www.lib.uct.ac.za/sites/default/files/image_tool/images/516/documents/UCT_Author_Date_referencing_2016.pdf). 

## Options
`style=authoryear-comp`: deals with papers written by the same author but in different years. Change to `authoryear` to have it repeat citations.

`maxcitenames=2`: for papers with more than 2 athors we cite first author and *et al.* (This is set to 2 here because of the Biology Faculty, but the official docs maintain it should be `3`).

`maxbibnames=8`: similar to the above but for the bibliography.

`giveninits=true`: uses initials rather than the full names in the bibliography.

## Further Docs

Find the full biblatex docs at http://ctan.math.washington.edu/tex-archive/macros/latex/contrib/biblatex/doc/biblatex.pdf. Specifically section 3.

## License

[Creative Commons Zero v1.0 Universal](https://choosealicense.com/licenses/cc0-1.0/)
