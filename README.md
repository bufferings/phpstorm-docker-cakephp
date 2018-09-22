# PhpStorm + Docker and CakePHP development

Please check this article:

https://medium.com/@bufferings/phpstorm-docker-and-cakephp-development-9327ee767838

# Sample commands

## Composer

```
❯ docker-compose run --rm php-cli composer --version
gosu user to www-data
Composer version 1.7.2 2018-08-16 16:57:12
```

## PHPCS

```
❯ docker-compose run --rm php-cli vendor/bin/phpcs --version
gosu user to www-data
PHP_CodeSniffer version 3.3.1 (stable) by Squiz (http://www.squiz.net)
```

## PHPMD

```
❯ docker-compose run --rm php-cli vendor/bin/phpmd --version
gosu user to www-data
PHPMD 2.6.0
```

## Start Apache

```
❯ docker-compose up -d
Starting phpstormdockercakephp_php-web_1 ... 
Starting phpstormdockercakephp_php-web_1 ... done
```

You can access the app with `localhost:8000`
