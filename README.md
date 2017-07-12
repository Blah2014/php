# php
PHP related stuff

***Please donate if you are using this repo***

***Note:*** If you found this project helpful please give this repo a star.

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=C2HFZWSUPV47Q" target="_blank">
  <img src="https://raw.githubusercontent.com/Blah2014/phonegap-inmobi-plugin/gh-pages/images/BuymeaCoffee.png" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!" />
</a>

<a href="http://traderhub.info" target="_blank">
  <img src="http://traderhub.info/images/AD.jpg" border="0" name="submit" alt="TraderHub - daily stock picks, market signals, stock picking service" />
</a>

### Index
* [Mac PHP XDebug Downloads](#mac-php-xdebug-downloads)
* [XDebug Wizard](#xdebug-wizard)
* [Sentiment Analysis](#sentiment-analysis)
* [jsonp_decode.php](#user-content-jsonp_decodephp)
* [PayPal REST API SDK for PHP](#paypal-rest-api-sdk-for-php)

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

