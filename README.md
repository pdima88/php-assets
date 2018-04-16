# s4y/assets
Small asset manager for PHP

## Usage:

Use add static method to include assets you need
```php
use s4y\Assets;
...
Assets::add('bootstrap');    // include asset library, defined in Assets::$libs
Assets::add('css/main.css'); // include single css file
Assets::add('js/script.js'); // include single js file
// or all at once:
Assets::add([
 'bootstrap',
 'css/main.js',
 'js/script.js'
]);
```
