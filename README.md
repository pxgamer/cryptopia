# cryptopia

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Style CI][ico-styleci]][link-styleci]
[![Code Coverage][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

An API wrapper for Cryptopia.co.nz

## Structure

```
src/
tests/
vendor/
```

## Install

Via Composer

```bash
$ composer require pxgamer/cryptopia
```

## Usage

### Basic methods

Initialise the `Basic` class.

```php
$basic = new pxgamer\Cryptopia\Basic();
```

Retrieve a list of currencies as an `array`.

```php
$basic->getCurrencies();
```

Retrieve a list of trade pairs as an `array`.

```php
$basic->getTradePairs();
```

Retrieve a list of markets as an `array`.

```php
$basic->getMarkets();
```

Retrieve a single market as a `stdClass`.

```php
$basic->getMarket();
```

Retrieve a single market's history as an `array`.

```php
$basic->getMarketHistory();
```

Retrieve a single market's orders as a `stdClass`.

```php
$basic->getMarketOrders();
```

Retrieve a list of market order groups as an `array`.

```php
$basic->getMarketOrderGroups();
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

```bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email owzie123@gmail.com instead of using the issue tracker.

## Credits

- [pxgamer][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/pxgamer/cryptopia.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/pxgamer/cryptopia/master.svg?style=flat-square
[ico-styleci]: https://styleci.io/repos/117662532/shield
[ico-code-quality]: https://img.shields.io/codecov/c/github/pxgamer/cryptopia.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/pxgamer/cryptopia.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/pxgamer/cryptopia
[link-travis]: https://travis-ci.org/pxgamer/cryptopia
[link-styleci]: https://styleci.io/repos/117662532
[link-code-quality]: https://codecov.io/gh/pxgamer/cryptopia
[link-downloads]: https://packagist.org/packages/pxgamer/cryptopia
[link-author]: https://github.com/pxgamer
[link-contributors]: ../../contributors
