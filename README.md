# php-ext-gtk-doc-en
English PHP documentation for Gtk+


build it
========

git clone https://github.com/php/web-php.git
git clone https://github.com/php/doc-base.git
git clone https://github.com/php/doc-en.git en
cd en
../doc-base/configure.php
phd -f php -d ../doc-base/.manual.xml -P PHP
cd ../web-php/manual && ln -s ../../en/output/php-web en

// -----------------------------------------

run it
======

$ cd ..
$ php -S localhost:8080 .router.php

http://localhost:8080/manual/en/function.chop.php


Add extension documentation
===========================

phpdoc/en/reference/gtk
phpdoc/en/reference/entities.gtk.xml



