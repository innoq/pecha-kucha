pecha kucha
===========

Template for pecha kucha slides in asciidoc format.

First you must have installed [asciidoctor](http://asciidoctor.org/).

Use `git clone --recursive` to download this repository along with its submodules.

Add your presentation and include it in `presentation/pecha-kucha.adoc` (just replace Sample.adoc)

You can build the presentation with this command:

    asciidoctor -T asciidoctor-backends/slim/revealjs/ presentation/pecha-kucha.adoc
    
Open the created file `presentation/pecha-kucha.html` in a browser.




