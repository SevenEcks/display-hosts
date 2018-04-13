# display-hosts

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

Pretty print a table with the hosts file for the OS using PHP.

## Installation

Via Composer

### Global

```bash
composer global require sevenecks/display-hosts
```

### Local
```bash
composer require sevenecks/display-hosts
```

### CLI Usage

#### Global Install
If you are on a system where the hosts file is located at /etc/hosts then you have no further configuration to do. If you are not, then you should go to the global composer directory, go into the vendor folder, copy the .env-example  file to .env and edit it to point to your hosts file. Then you can proceed.

```bash
DisplayHosts
```

#### Local Install
If you are on a system where the hosts file is located at /etc/hosts then you have no further configuration to do. If you are not, then you should go into the vendor folder, copy the .env-example  file to .env and edit it to point to your hosts file. Then you can proceed.

```bash
./vendor/bin/DisplayHosts
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email bbutts@stormcode.net instead of using the issue tracker.

## Credits

- [Brendan Butts][link-author]
- [All Contributors][link-contributors]

## Change Log
Please see [Change Log](CHANGELOG.md) for more information.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/sevenecks/display-hosts.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/sevenecks/display-hosts/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/sevenecks/display-hosts.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/sevenecks/display-hosts.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/sevenecks/display-hosts.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/sevenecks/display-hosts
[link-travis]: https://travis-ci.org/sevenecks/display-hosts
[link-scrutinizer]: https://scrutinizer-ci.com/g/sevenecks/display-hosts/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/sevenecks/display-hosts
[link-downloads]: https://packagist.org/packages/sevenecks/display-hosts
[link-author]: https://github.com/sevenecks
[link-contributors]: ../../contributors
