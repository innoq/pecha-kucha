pecha kucha
===========

Template for pecha kucha slides in asciidoc format.

First you must have installed [asciidoctor](http://asciidoctor.org/).

After `git clone` of this repo init sub modules to get asciidoc-backend and reveal.js:

    git submodule init

    git submodule update

Add your presentation and include it in `presentation/pecha-kucha.adoc` (just replace Sample.adoc)

You can build the presentation with this command:

    asciidoctor -T asciidoctor-backends/slim/revealjs/ presentation/pecha-kucha.adoc
    
Open the created file `presentation/pecha-kucha.html` in a browser.




