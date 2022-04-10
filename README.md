![FortifyTablerAdmin](https://bitbucket.org/akukoder/fortify-tabler-admin/raw/43ab4d3cb0ee8849349ae4995fb1b7c253db70c9/fortify-tabler-admin.png)

# Introduction

[![Latest Version on Packagist](https://img.shields.io/packagist/v/akukoder/fortify-tabler-admin.svg?style=flat-square)](https://packagist.org/packages/akukoder/fortify-tabler-admin)
[![Last Commit](https://img.shields.io/bitbucket/last-commit/akukoder/fortify-tabler-admin?style=flat-square)](https://packagist.org/packages/akukoder/fortify-tabler-admin)
[![Total Downloads](https://img.shields.io/packagist/dt/akukoder/fortify-tabler-admin.svg?style=flat-square)](https://packagist.org/packages/akukoder/fortify-tabler-admin)
[![License](https://img.shields.io/packagist/l/akukoder/fortify-tabler-admin?style=flat-square)](https://packagist.org/packages/akukoder/fortify-tabler-admin)

**FortifyTablerAdmin** is a Laravel Fortify UI preset, built with an open source [Tabler Admin Theme](https://tabler.io).

## Features

All Fortify features enabled by default, and some other basic features to get you started.

1. Login
2. Registration
3. Reset password
4. Email verification
5. Profile Information
6. Update password
7. Two-factor authentication
8. Browser session
9. User management
10. Multiple dashboard layouts to choose
11. Light or dark theme (per user setting)

## Requirement

Install the package on the new **Laravel 8 and above** only, without additional packages like Jetstream or Laravel Ui. Laravel Fortify and FortifyUI will be installed automatically.

## Installation

To get started, you'll need to install **FortifyTablerAdmin** using composer.

```shell
composer require akukoder/fortify-tabler-admin --dev
```

Next, you'll need to run the install command:

```shell
php artisan fortify:tabler
```

Then you can select which layout you want to use in your app. There are 3 layouts available:

1. [Horizontal](https://preview.tabler.io/layout-horizontal.html)
2. [Overlap](https://preview.tabler.io/layout-navbar-overlap.html)
3. [Vertical](https://preview.tabler.io/layout-vertical.html)
3. [Vertical Transparent](https://preview.tabler.io/layout-vertical-transparent.html)

*You can view the demo for each layout from Tabler official demo.*

## Changing Layout

If you want to change the layout, just execute this command:

```shell
php artisan fortify:layout
```

## Documentation

For the documentations, please refer to the official websites.

- [Tabler](https://tabler.io)
- [Bootstrap 5](https://getbootstrap.com/)
- [Fortify UI](https://github.com/zacksmash/fortify-ui)
- [Intervention Image](https://github.com/intervention/image)
- [Arcanedev Laravel Settings](https://github.com/ARCANEDEV/LaravelSettings/)

## Screenshot

![FortifyTablerAdmin Screenshot](https://bitbucket.org/akukoder/fortify-tabler-admin/raw/8d605c5f8b26ca4b4690fd6e60434390a0f2a9f0/screenshot.png)

### Horizontal (Default)
![Horizontal Layout](https://bitbucket.org/akukoder/fortify-tabler-admin/raw/8d605c5f8b26ca4b4690fd6e60434390a0f2a9f0/screenshot-horizontal.png)

### Overlap
![Overlap Layout](https://bitbucket.org/akukoder/fortify-tabler-admin/raw/8d605c5f8b26ca4b4690fd6e60434390a0f2a9f0/screenshot-overlap.png)

### Vertical
![Vertical Layout](https://bitbucket.org/akukoder/fortify-tabler-admin/raw/8d605c5f8b26ca4b4690fd6e60434390a0f2a9f0/screenshot-vertical.png)

### Vertical Transparent
![Vertical Transparent Layout](https://bitbucket.org/akukoder/fortify-tabler-admin/raw/8d605c5f8b26ca4b4690fd6e60434390a0f2a9f0/screenshot-vertical-transparent.png)

## Credits
- [Fortify UI](https://github.com/zacksmash/fortify-ui)
- [Tabler](https://tabler.io)
- [Proxeuse](https://github.com/Proxeuse/fortify-tabler)

## License

**FortifyTablerAdmin** is open-sourced software licensed under the [MIT license](LICENSE.md).
