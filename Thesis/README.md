# thesisTemplate

A PhD thesis template for the School of Mathematics, Monash University 

## Compiling said template

### Using an editor like TeXworks

To compile the document with an editor like TeXworks you will need to compile from the thesis.tex file. Compiling from a chapter will not work!

The standard compilation procedure when using BibTeX will apply.

1) Compile with pdflatex to generate aux files,

2) run bibtex to register bibliography references,

3) compile with pdflatex twice to correctly render references.

### Using commandline on a Unix like system

Ensure you have texlive installed correctly.

Run the following command:

```
$ pdflatex thesis.tex & bibtex thesis.aux & pdflatex thesis.tex & pdflatex thesis.tex
```

## Other notes

For your own sanity you should keep the structure of this template. That means putting thesis chapters in the correct folder. Placing preamble in the preamble document and not including anything in thesis.tex that is not meant to be there. Help us, help you!

If you have any suggestions please email [Kaustav Das](mailto:kautav.das@monash.edu) or [Michael Gill](mailto:michael.gill@monash.edu)
