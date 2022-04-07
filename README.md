# Contingency and Apotheosis in Sartrean Metaphysics

*An Investigation into the Question of Whether Love and Philosophy are Possible*

An Essay written by Shen Zhou Hong, in fulfilment of a Bachelor's Degree in the Liberal Arts, at St. John's College.

![Hummingbird and Apple Blossoms - painting by Martin Johnson Heade. Public Domain, image source: Wikimedia Commons.](apple-blossoms.jpg)

## Introduction/Précis

What does it mean to be human? What does it mean to be? These are the eternal questions of Philosophy, the inquiries which aim to ground the experiences of our human reality. Metaphysics is the proper study of these questions, and Jean-Paul Sartre’s Being and Nothingness is a monograph which presents an entirely novel account of metaphysics as we know it – where the foundation of our ontology as conscious, human beings comes not from being at all, but rather from nothingness. 

Our consciousness is a being to whom phenomena appears to, this much is clear. But what is the being-of-phenomena in itself? Sartre defines the being-of-phenomena as the non-being of the being of consciousness, and with that single act, he introduces nothingness as the fundamental force of his metaphysics. This nothingness yields a rich, metaphysical universe which accounts for the vivid plenum of phenomena within our human-reality – but on the other hand, introduces a troubling impossibility that is difficult to ignore. 

This impossibility is love. 

For by founding our ontology upon nothingness, our very being becomes contingent. And as a result of this deduction, the ontological relationship of love as a relation between two beings, is coloured by this contingency. Hence love, in Sartre’s eyes, is a conflict between two freedoms – where the very project of love is an attempt of our contingent being to derive a foundation for its being. In other words, love tries to fill the very nothingness which both troubles us, and yet defines who we are.  

This attempt is ultimately futile, and self-defeating – a reductio which is demonstrated with the full force of Sartrean metaphysics. 

I disagree with this demonstration. And the project of my essay, is an attempt – to ask if there is any possible account for love, within Phenomenological Metaphysics at all. 

I say that there is an account. This account is philosophy, as the love of wisdom. Where the ontological act of philosophy is a pursuit of being, but one to which its object admits no contingency. For all philosophy is a pursuit of being: when we ask “what is virtue”, or “what is good,” we are ultimately asking, what is the characteristic activity of a human being. And it is in this pursuit of being, that we arrive at the ultimate being – the being which is the cause of itself, the Prime Mover, God.  

This pursuit of the ultimate being resolves the troubling impossibility of Sartre- there exists a modality of love which is consistent and authentic with the original ontological act. Man is a creature who seeks in its being, a foundation for its being—an apotheosis that is achievable perhaps only through philosophy.  

This is the subject of my essay, on Contingency and Apotheosis in Sartrean Metaphysics. It is an investigation into whether or not, Love and Philosophy, are Possible at all. 

## Accessing document
A PDF version of this essay is available at the following link:

* [**Contingency and Apotheosis in Sartrean Metaphysics**](./latex/sartre-essay.pdf)
* [**Précis (Summary)**](./precis.md)

## Compiling document

In order to compile the document from the original latex source files, run `make` in the terminal:

```
cd latex
make
make clean
```

Note: for any partial compiles where compilation fails at a certain point, you
should run `make clean` followed by make again. Trying to run make after a
failed compile would result in additional errors.

## Dependencies
This template uses a makefile to compile the latex source files. The makefile
uses `latexmk`, which runs latex the correct number of times. This is because
due to the presense of figures, tables, and biblatex databases, latex needs to
be called multiple times in some cases. Latexmk should be included in your
latex installation, but if it is now, you may download it here:

* http://personal.psu.edu/jcc8//software/latexmk-jcc/

Additionally, this template uses LuaLaTeX by default, as it allows
the inclusion of unicode characters in the latex source files. If XeLaTeX is
not installed, or plain LaTeX is required, simply alter the `makefile` at the
appropriate call:

```
# MAIN LATEXMK RULE
$(source_name).pdf: $(source_name).tex
  ...
	latexmk -pdf -lualatex -use-make $<
```

### Related documentation
For an overview of how to populate biblatex `citations.bib` files, visit the
biblatex-mla manual at CTAN.

* https://www.ctan.org/pkg/biblatex-mla

### GPLv3 License
The raw template itself is licensed under the terms of the GPL (version 3). A
full copy of the license is attached in `LICENSE.md`. Naturally, any works
that you create using this template (i.e. any actual essays you write using
it) will be your own intellectual property. The GPLv3 license only applies to
any derivative templates.
