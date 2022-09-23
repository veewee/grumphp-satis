# Installation

```
kevin up
```

## Manual build

```
echo '/app/scripts/build.sh' | kevin ssh satis 
```


## Contains:

```
"phpro/grumphp-shim": "1.13",
"phpunit/phpunit": "9.5.24",
"friendsofphp/php-cs-fixer": "3.11.0"
```

and deps.

## Usage

```
{
  "repositories": [{
    "type": "composer",
    "url": "http://127.0.0.1:8000"
  }]
}
```