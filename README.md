# CZ Routines - tiny toolkit for Czech strings and names

# CZ Names

Tooling for normalizing names

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist alav24/cz-routines "*"
```

or add

```json
"alav24/cz-routines": "*"
```

to the `require` section of your composer.json.

## Usage

```php
use aval24\czroutines\CZNames;

$name = "Mgr. JANA TALÁKOVÁ";

$test1 = CZNames::purge($name);

echo "Source: $name\n"; 
echo "Result: $test1\n";

```
