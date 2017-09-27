# php
PHP related stuff

***Please donate if you are using this repo***

***Note:*** If you found this project helpful please give this repo a star.

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=C2HFZWSUPV47Q" target="_blank">
  <img src="https://raw.githubusercontent.com/Blah2014/phonegap-inmobi-plugin/gh-pages/images/BuymeaCoffee.png" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!" />
</a>

### Index
* [Mac PHP XDebug Downloads](#mac-php-xdebug-downloads)
* [XDebug Wizard](#xdebug-wizard)
* [Sentiment Analysis](#sentiment-analysis)
* [jsonp_decode.php](#user-content-jsonp_decodephp)
* [PayPal REST API SDK for PHP](#paypal-rest-api-sdk-for-php)
* [JSON Web Token Authentication for Laravel & Lumen](#user-content-json-web-token-authentication-for-laravel--lumen)
* [Encryption](#encryption)
* [HTTPS](#https)

##### PHP HTTP clients
* [Guzzle is a PHP HTTP client that makes it easy to send HTTP requests and trivial to integrate with web services](#user-content-guzzle-is-a-php-http-client-that-makes-it-easy-to-send-http-requests-and-trivial-to-integrate-with-web-services)
* [Goutte is a screen scraping and web crawling library for PHP](#user-content-goutte-is-a-screen-scraping-and-web-crawling-library-for-php)

### Mac PHP XDebug Downloads#
[Mac PHP XDebug Remote Debugging Package Downloads](http://code.activestate.com/komodo/remotedebugging/)

### XDebug Wizard
[Tailored Installation Instructions](https://xdebug.org/wizard.php)

### Sentiment Analysis
[phpInsight - Sentiment Analysis in PHP](https://github.com/JWHennessey/phpInsight)

### jsonp_decode.php
```php
<?php
   $jsonp_string = preg_replace("/[^(]*\((.*)\)/", "$1", file_get_contents("http://api.pinterest.com/v1/urls/count.json?callback=receiveCount&url=http://9gag.com/"));
   $json = json_decode($jsonp_string, true);
   echo $json['count'];
?>
```

### Guzzle is a PHP HTTP client that makes it easy to send HTTP requests and trivial to integrate with web services
[Guzzle](https://github.com/guzzle/guzzle)
### Goutte is a screen scraping and web crawling library for PHP
[Goutte](https://github.com/FriendsOfPHP/Goutte)

### PayPal REST API SDK for PHP
* [REST API SDK for PHP](https://github.com/paypal/PayPal-PHP-SDK)
* [REST API Samples](http://paypal.github.io/PayPal-PHP-SDK/sample/)

### JSON Web Token Authentication for Laravel & Lumen
[JSON Web Token Authentication for Laravel & Lumen](https://github.com/tymondesigns/jwt-auth)

### Encryption
* [php-openssl-cryptor](https://github.com/ioncube/php-openssl-cryptor)

### HTTPS
* [SSL FOR FREE](https://www.sslforfree.com)
* [Acme PHP](https://acmephp.github.io/)
* [Let’s Encrypt is a free, automated, and open](https://letsencrypt.org/)
