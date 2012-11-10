Sphinx Search PHP Client
========================

[Sphinx] [1] is an open source full-text search engine.

This project contains a refactored Sphinx PHP client with some minor differences:

* Compatibility with [Composer] [2]
* Compliance with [PSR standards] [3]
* Fluent (chainable) setter functions
* PHPUnit tests

Installation
------------

Create a `composer.json` file and run `composer install`:

    {
        "minimum-stability": "alpha",
        "repositories": [
            {
                "type": "vcs",
                "url": "http://github.com/gigablah/sphinxphp"
            }
        ],
        "require": {
            "gigablah/sphinxphp": "2.0.6-alpha"
        }
    }

Usage
-----

Refer to the official [documentation] [4].

Note: public functions have been changed to lower camelcase in accordance with PSR-1.

License
-------

GNU General Public License version 2 ([GPL-2.0] [5])

[1]: http://sphinxsearch.com/
[2]: http://getcomposer.org/
[3]: https://github.com/php-fig/fig-standards
[4]: http://sphinxsearch.com/docs/
[5]: http://www.gnu.org/licenses/gpl-2.0.html