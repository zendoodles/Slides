ZenDoodles Slide Decks
======================

Currently, all of my presentations are Symfony and Reveal.js-based. I've used
 a basic Symfony project and added the [KnpRevealBundle][1] from KNP Labs to build
 my decks. You're welcome to fork this for your own presentations. The master
 branch is a generic starting point where you can create a new branch and
 start your new presentation.

I also recommend the documentation for [Reveal.js][2] and [Symfony][3].

Each time I speak, I'll create a tag, so if you're looking for slides from a
 specific session check out the tag for your session. See the instructions below
 to view the slides locally.

Installing
-------------
This is pretty much the standard Symfony install. If you have problems, do see
 the [Installation][4] chapter of the Symfony Documentation.

After you've cloned or downloaded, you'll just install the dependencies with
 `composer install`

If you don't have Composer yet, get it following the [instructions on
 GetComposer.org][5] or just run  `curl -s http://getcomposer.org/installer | php`
 Then install the dependencies with `php composer.phar install`.

To make sure that your local system is properly configured for Symfony, execute
 the `check.php` script from the command line:

    php app/check.php

The script returns a status code of `0` if all mandatory requirements are met,
`1` otherwise.

Access the `config.php` script from a browser:

    http://localhost/path-to-project/web/config.php

If you get any warnings or recommendations, fix them before moving on.

Browsing the Demo Slides
---------------------------

From the `config.php` page, click the "Bypass configuration and go to the
Welcome page" link to load the demo slide deck.


Enjoy!

[1]:  https://github.com/KnpLabs/KnpRevealBundle
[2]:  http://lab.hakim.se/reveal-js
[3]:  http://symfony.com/doc/current/quick_tour/the_big_picture.html
[4]:  http://symfony.com/doc/2.4/book/installation.html
[5]:  http://getcomposer.org/
