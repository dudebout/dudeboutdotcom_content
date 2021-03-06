# Projects

## game-theoretic-learning

[game-theoretic-learning](http://github.com/dudebout/game-theoretic-learning) is a library written in Haskell for studying game-theoretic learning through simulation.
This library was first used to [illustrate the learnability of empirical-evidence equilibria](http://github.com/dudebout/cdc_2012_dudebout_shamma/tree/master/simulations).
It accomodates arbitrary numbers of players by using [HLists](http://hackage.haskell.org/package/HList) as variable-length tuples.
I coded helper functions for this use case and made them available on Hackage under the name [tuple-hlist](http://hackage.haskell.org/package/tuple-hlist).

## matrix.skeleton

[matrix.skeleton](http://github.com/dudebout/matrix.skeleton) is a [PGF/TikZ](http://www.texample.net/tikz/) library that simplifies working with multiple matrix nodes. To do so, matrix.skeleton correctly aligns groups of nodes with the content of the whole matrix.
Furthermore, matrix.skeleton provides rows and columns for easy styling.
More information and examples are available in [the manual](/files/pdfs/matrix.skeleton-manual.pdf).

## LaTeX

<div class="meta-p">
  When writing LaTeX documents, I reuse as much code as possible.
  To avoid repeating myself, I packaged useful code.
  I then use these packages to populate a local <span class="filename">texmf</span> tree with Git submodules.
  My packages include:

  + [bibtex_ddb](http://github.com/dudebout/bibtex_ddb): BibTeX files containing all my citations
  + [latex_ddbbeamer](http://github.com/dudebout/latex_ddbbeamer): collection of Beamer themes
  + [latex_ddbbib](http://github.com/dudebout/latex_ddbbib): packages to use my BibTeX files
  + [latex_ddbgame](http://github.com/dudebout/latex_ddbgame): configuration for [sgame](http://www.ctan.org/tex-archive/macros/latex/contrib/sgame) and code to use strategic form games as equations instead of figures
  + [latex_ddbref](http://github.com/dudebout/latex_ddbref): default settings for [hyperref](http://www.ctan.org/tex-archive/macros/latex/contrib/hyperref) and [cleveref](http://www.ctan.org/tex-archive/macros/latex/contrib/cleveref)
  + [latex_ddbsymb](http://github.com/dudebout/latex_ddbsymb): set of macros for common LaTeX constructs
  + [latex_ddbthm](http://github.com/dudebout/latex_ddbthm): list of theorems and theorem styles
  + [latex_ddbinfo](http://github.com/dudebout/latex_ddbinfo): author information used in all my publications
  + [latex_ddbieee](http://github.com/dudebout/latex_ddbieee): code to comply with IEEE's requirements automatically
  + [latex_ddbglossaries](http://github.com/dudebout/latex_ddbglossaries): extension for [glossaries](http://www.ctan.org/tex-archive/macros/latex/contrib/glossaries) inserting the appropriate indefinite article for acronyms

</div>


## dudebout.com

The [code](http://github.com/dudebout/dudeboutdotcom) and the [content](http://github.com/dudebout/dudeboutdotcom_content) of this website are available on GitHub.
It runs on [Yesod](http://yesodweb.com) and [Bootstrap](http://getbootstrap.com).
Most pages are written in Markdown with the exception of [the résumé](resume), generated from YAML, and [the list of publications](publications) from BibTeX.


## .emacs.d

<div class="meta-p">
  [Emacs configuration](http://github.com/dudebout/emacs_init) split into:

  + <span class="filename">init.el</span>: code to install new packages at startup and calls to functions defined in <span class="filename">ddb-conf.el</span>
  + <span class="filename">ddb-conf.el</span>: actual configuration code organized by modes
  + <span class="filename">ddb-interactives.el</span>: interactive functions accumulated over the years

</div>
