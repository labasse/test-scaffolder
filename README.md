# test-scaffolder

A php functional test scaffolder for webdriver and phpunit using maker.

## Installation

Installation is possible using Composer.

If you don't already use Composer, you can download the `composer.phar` binary:

```bash
    curl -sS https://getcomposer.org/installer | php
```

Then install the library:

```bash
    php composer.phar require "syllab/test-scaffolder"
```

## Usage

Here are the commands available:

- `php bin/console webtest:init`: Initialize a new test project
- `php bin/console webtest:class`: Create a new test class

You can get this list by running `php bin/console list` in your terminal or get help on each command using `php bin/console (command) --help`.
