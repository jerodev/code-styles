# PHP code styles
phpcs rules for my own projects.

## How to use
Install this package and create a `phpcs.xml` file in the root of the project with the following content:

```
<?xml version="1.0"?>
<ruleset xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" name="PhpCs_AnyFinder" xsi:noNamespaceSchemaLocation="./vendor/squizlabs/php_codesniffer/phpcs.xsd">
    <rule ref="./vendor/jerodev/code-styles/phpcs.xml" />

    <file>app</file>
    <file>..</file>
</ruleset>

```

Now the codesniffer can be ran using:

```
./vendor/bin/phpcs -p
```
