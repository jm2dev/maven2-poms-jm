DocBook 5 with maven
====================

José Miguel Martínez Carrasco
July 17, 2011

Overview
--------

This is a simple project to illustrate the generation of documentation from DocBook5 sources using maven.

Requisites
----------

* maven3
* openjdk 7

Although it is supposed to work with maven2 and any java sdk newer than 1.4.

Usage
-----

```sh
mvn docbkx:generate-html
xdg-open target/docbkx/html/article/article.html
```

References
----------

* http://docbkx-tools.sourceforge.net/docbkx-maven-plugin/plugin-info.html
* http://code.google.com/p/docbkx-tools/


