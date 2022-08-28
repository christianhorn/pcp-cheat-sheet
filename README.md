# Performance Co-Pilot (PCP) cheat sheet

## What's this?

This cheat sheet is my attempt to have one place to recall the commands
around PCP which I need every now and then.  This is not intended as a
'I read this cheat sheet, and then know PCP'-doc, but as a place for 
someone who got an introduction into the PCP core concepts, to recall
commands.

## Building the pdf

- Install the LaTeX dependencies (TODO, refer to i.e. the package names
  on Fedora)
- Clone this repo, run pdflatex
```
git clone https://github.com/christianhorn/pcp-cheat-sheet
cd pcp-cheat-sheet
pdflatex pcpcheat.tex
```
or via make
```
git clone https://github.com/christianhorn/pcp-cheat-sheet
cd pcp-cheat-sheet
make
```

## Known bugs

- I have content to start a second page, but maybe cheat sheets should 
  concentrate on what fits to one page.  Also, tcolorbox[poster] only
  supports a single page.
