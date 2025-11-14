# Welcome
This is an Asciidoc book of Tudor Girba and Simon Wardley's "Rewilding Software Engineering". It simply takes all their [medium posts](https://medium.com/feenk) and joins them together for ease of reading.  The intention is to be entirely faithful to the original posts - I've not even fixed the few spelling mistakes - while allowing various output versions to be generated, e.g. HTML, and .mobi for Kindle e-readers.  It is made available under the same Creative Commons Attribution-ShareAlike-4.0-International licence as the original posts.

This project borrows inspiration and more from Andrew Harmel-Law's work on the Wardley Mapping book, also on https://github.com/andrewharmellaw/wardley-maps-book[github]

# Generating the book yourself
All these generators require you to have installed [asciidoctor](https://asciidoctor.org/docs/user-manual/). Then select the command you require to generate the output you desire.

## HTML 
To generate the HTML version of this book, run the following command in the base directory of this repository:

    asciidoctor wardley-maps-book.adoc

## PDF
To generate the PDF version of this book, you additionally need to install [asciidoctor-pdf](https://asciidoctor.cn/docs/convert-asciidoc-to-pdf/) with the following command:

    gem install --pre asciidoctor-pdf

Then you can run the following command in the base directory of this repository:

    asciidoctor-pdf wardley-maps-book.adoc

# Contributing
Contributions are cool, and also very welcome.  There is a [contribution guide](CONTRIBUTING.md) which you can familiarise yourself with if you want to get involved (even if its just fixing a typo).  They should be _very_ unsurprising to anyone used to the OSS world.

