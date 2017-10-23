# Lumen-Modules

Simplified version of [laravel-modules](https://github.com/nWidart/laravel-modules), fit to use in [Lumen 5.5](https://lumen.laravel.com/)

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)

`stoykov/lumen-modules` is a Lumen package which created to manage your large Lumen app using modules. Module is like a Lumen package, it has some views, controllers or models. This package is supported and tested in Lumen 5.5.

This package is a simplified version of [laravel-modules](https://github.com/nWidart/laravel-modules) with only Lumen support in mind, it has the bare minimum to be able to serve modules.

Find out why you should use this package in the article: [Writing modular applications with laravel-modules](https://nicolaswidart.com/blog/writing-modular-applications-with-laravel-modules).

## Install

To install through Composer, by run the following command:

``` bash
composer require stoykov/lumen-modules
```

The package will automatically register a service provider and alias.

### Autoloading

By default the module classes are not loaded automatically. You can autoload your modules using `psr-4`. For example:

``` json
{
  "autoload": {
    "psr-4": {
      "App\\": "app/",
      "Modules\\": "Modules/"
    }
  }
}
```

**Tip: don't forget to run `composer dump-autoload` afterwards.**

## Documentation

You'll find installation instructions and full documentation on [https://nwidart.com/laravel-modules/](https://nwidart.com/laravel-modules/).

## Credits

- [Nicolas Widart](https://github.com/nwidart)
- [gravitano](https://github.com/gravitano)
- [Antoan Stoykov](https://github.com/stoykov)
- [All Contributors](https://github.com/nWidart/laravel-modules/contributors)


## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
