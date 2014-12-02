Sublime Text 3 - Dot Files
==========================

https://sublime.wbond.net/docs/syncing

Installation
------------

After installing Sublime Text 3, [install package manager](https://sublime.wbond.net/installation)

cd %USERPROFILE%\AppData\Roaming\Sublime Text 3\Packages
rm -rf User
git clone https://github.com/mac2000/st3.git User

For snippets to see current scope press: `Ctrl + Alt + Shift + P`, current scope will be shown in bottom left conrer of status bar.


Dependencies
------------

SublimeLinter
http://www.sublimelinter.com/en/latest/installation.html

SublimeLinter-csslint
https://github.com/SublimeLinter/SublimeLinter-csslint
npm install -g csslint

SublimeLinter-jshint
https://github.com/SublimeLinter/SublimeLinter-jshint
npm install -g jshint

SublimeLinter-php
https://github.com/SublimeLinter/SublimeLinter-php

SublimeLinter-phpcs
https://github.com/SublimeLinter/SublimeLinter-phpcs
composer global require "squizlabs/php_codesniffer=x"

SublimeLinter-phpmd
https://github.com/SublimeLinter/SublimeLinter-phpmd
composer global require "phpmd/phpmd=x"
