ISO-639
================

- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)


Usage
-----

``` php
use ISO638\Languages;

// from getter
$languages = (new Languages())->getLanguages();
var_dump($languages);

// or as static public array inside Language class
$languages = Languages::$languages;
var_dump($languages);
```


Installation
------------

Add the iso-639 package to your `composer.json` file.

``` json
{
    "require": {
        "keo/iso-639": ">=1.0"
    }
}
```

Or via the command line in the root of your Laravel installation.

``` bash
$ composer require "keo/iso-639:1.0*"
```


Contributing
------------

Just make issue or pull request.



License
-------

The MIT License (MIT). Please see [License File](https://github.com/SammyK/package-skeleton/blob/master/LICENSE) for more information.
