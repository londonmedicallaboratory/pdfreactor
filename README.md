# RealObjects PDFreactor® PHP wrapper

PHP wrapper API for PDFreactor (PHP include, PHP sample), put into a composer-compatible library package for Symfony which
autoloads the PDFreactor wrapper.

Used from PDFreactor.com PHP Client V9

Please note that by installing and using PDFreactor itself (not the wrapper) you agree to the license, terms and
conditions of PDFreactor.com.

This package is not affiliated with RealObjects or PDFreactor.

## Usage

Use composer to install the library via `composer require londonmedicallaboratory/pdfreactor`.

In an ideal world, you then have your composer-based application and just use it like this:

    $pdfReactor = new PDFreactor('http://yourServer:9423/service/rest');

as the class is already available via the composer autoloader.

## License

The PDFreactor wrapper library is licensed under MIT, see LICENSE file for more details.
