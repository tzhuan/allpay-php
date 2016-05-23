# tzhuan/allpay-aio-php

Composer package for [allpay](https://www.allpay.com.tw)'s AIO PHP SDK


## Installation

Add the following lines to your `composer.json` and run `composer install`.

```json
"repositories": [
    {  
        "type": "vcs",
        "url": "https://github.com/tzhuan/allpay-aio-php"
    }
],
"require": {
    "tzhuan/allpay-aio-php": "*"
}
```

## Usage

```php
require 'vendor/autoload.php';

$aio = new AllInOne();

```

Please see `AioSDK/manual/歐付寶金流整合SDK技術文件(PHP版).pdf` for more information.
