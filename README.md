# About 

Project site: https://github.com/de-jcup/eclipse-asciidoctor-testprojects

It just contains some eclipse testprojects for [eclipse asciidoctor editor](https://github.com/de-jcup/eclipse-asciidoctor-editor)- for bugfixing, common examples, best practices etc.


# Why?
It is sometimes very difficult to fix bugs in [eclipse asciidoctor editor](https://github.com/de-jcup/eclipse-asciidoctor-editor)  or to understand other project setups which lead to a reported behaviour.

# How to contribute?
If you have got a problem with eclipse asciidoctor editor please report an issue as usual at the [issue tracker](https://github.com/de-jcup/eclipse-asciidoctor-editor/issues). If you think your setup is not like standard setup or one of the already existing testprojects, do following:

## Initial
- clone this repo
- checkout master branch

## Complete other setup
When you have got a complete other project setup/structure than any of the example projects, please do following:

- create a new eclipse project in a dedicated subfolder of this repo
  (Name should be short and clear and follow name pattern: "asciidoctor-testproject{$Number}-{$shortDescription})"
- create your asciidoc files in your project like your setup where you have problems with
- commit, push ...
- create PR on GitHub

## Like existing testproject but with some additional parts
When you have a similar project setup as one of the existing testprojects, please add an own asciidoc file containing the problematic part. After this...

- commit, push ...
- create PR on GitHub



