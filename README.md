# Generate a Guide

*This project has been archived, any code / packages are likely obsolete and should not be reused.*

# Generate a Book

Please, run: 

    gradle publishGuide

    groovy book.groovy

Please follow the instructions to install the [asciidoctor-epub3](http://asciidoctor.org/docs/convert-asciidoc-to-epub/) ruby gem

generate the book:

    asciidoctor-epub3 -D build/bookOutput build/book/creating-your-first-grails-app.adoc

