Katayuno Octubre 2012 - Kata Tennis
==================================

http://agilecyl.org/2012/10/11/katayuno-27-de-octubre-valladolid/
http://www.solveet.com/exercises/Kata-Tennis/13
http://codingdojo.org/cgi-bin/wiki.pl?KataTennis

Instalación
===========

composer (http://getcomposer.org/doc/00-intro.md#installation)

$ curl -s http://getcomposer.org/installer | php
$ php composer.phar install

If you install composer globally (http://getcomposer.org/doc/00-intro.md#globally),
you should be use packagist :) (http://packagist.org/)

$ composer create-project isidromerayo/kata-tennis my_project_name

Uso
===

Crear los ejemplos o test en el directorio "tests".
Crear tú código fuente en el directorio  "src".

$ vendor/bin/phpunit -c tests/

Si quiere generar la cobertura de código (needs install xdebug extension)

$ vendor/bin/phpunit

Si quieres utilizar ant (and only phpunit task)

$ ant phpunit

Si utilizas Netbeans PHP, necesitas configurar:

* Project properties -> sources -> Test Folder: tests (Alt + F6 to run)
* Project properties -> PHPUnit -> use bootstrap: XXX/tests/TestHelper.php

Travis-CI
=========

Status build: [![Build Status](https://secure.travis-ci.org/isidromerayo/kata-tennis.png)](http://travis-ci.org/isidromerayo/kata-tennis)
