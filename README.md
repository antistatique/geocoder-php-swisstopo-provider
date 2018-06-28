# Swisstopo provider for Geocoder PHP


This is the [Swisstopo](https://www.geo.admin.ch/) provider for the [PHP Geocoder](https://github.com/geocoder-php/Geocoder), which uses the [PDOK Locatieserver v3 (Dutch)](https://www.pdok.nl/nl/producten/pdok-locatieserver).
It can geocode addresses (not IP addresses) and reverse geocode coordinates.

Please note that this provider can only (reverse) geocode addresses in Switzerland!

## Install

```bash
composer require antistatique/geocoder-php-swisstopo-provider
```

### HTTP Client

PHP Geocoder is decoupled from any HTTP messaging client with the help of [PHP-HTTP](http://php-http.org/).
This requires another package providing [php-http/client-implementation](https://packagist.org/providers/php-http/client-implementation).
To use Guzzle 6, for example, simply require `php-http/guzzle6-adapter`:

``` bash
composer require php-http/guzzle6-adapter
```

## Usage

### Options

### Response
