pecha kucha
===========

Template for pecha kucha slides in asciidoc format.

First you must have installed [asciidoctor](http://asciidoctor.org/).

Use `git clone --recursive` to download this repository along with its submodules.

Add your presentation and include it in `presentation/pecha-kucha.adoc` (just replace Sample.adoc)

You can build the presentation with this command:

    asciidoctor -T asciidoctor-backends/slim/revealjs/ presentation/pecha-kucha.adoc
    
Open the created file `presentation/pecha-kucha.html` in a browser.


Speaker Notes
-------------

&helli; can be added by adding the following below a slide's contents:

    [NOTE.speaker]
    --
    lorem ipsum
    dolor sit amet
    --

In order to display speaker notes, the presentation needs to be served via HTTP
(e.g. using python -m SimpleHTTPServer): Hitting `s` opens them in an
additional window.

