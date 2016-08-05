# php
PHP related stuff

### Index
* [Mac PHP XDebug Downloads](#mac-php-xdebug-downloads)
* [XDebug Wizard](#xdebug-wizard)
* [Sentiment Analysis](#sentiment-analysis)

### Mac PHP XDebug Downloads
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
