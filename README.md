# String Utils

---

Simple string utils for dealing easier with them

# Installation

Install using composer:

‌```
composer require hstring/string-utils
‌```

# Example

 ```
<?php
require __DIR__.'/vendor/autoload.php';

use \HString\StringUtils\Str;

var_dump(Str::contains('abcd', ['ab', 'x']));
 ```