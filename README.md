# gminify
Package for minify HTML, JS, CSS code

## Install

You will need [Composer](http://getcomposer.org) installed.

Add to your composer.json file this git repo
```bash
"repositories":[
    {
	      "type": "git",
	      "url": "http://github.com/gulch/gioptima"
    }
]
```
and add to require section
```bash
"require": {
    "gulch/gioptima": "dev-master"
}
```
and finally run
```bash
composer update
```

## Usage

```php
require 'vendor/autoload.php';

use gulch\GMinify;

$minified_html_code = GMinify::minifyHTML($your_html_code);
```
