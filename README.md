# numeric-postfix

## Installation

Via Composer

``` bash
$ composer require marysoul/numeric-postfix
```

## Usage

``` php
<?php

use function MaruSoul\NumericPostfix\getNumericPostfix;

require_once("vendor/autoload.php");

echo getNumericPostfix(1, 'апельсин', 'апельсина', 'апельсинов'); //апельсин
echo getNumericPostfix(3, 'апельсин', 'апельсина', 'апельсинов'); //апельсина
echo getNumericPostfix(5, 'апельсин', 'апельсина', 'апельсинов'); //апельсинов

echo getNumericPostfix(-148.15, 'апельсин', 'апельсина', 'апельсинов'); //апельсинов

```

