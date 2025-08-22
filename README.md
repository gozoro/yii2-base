# yii2-base
My yii2 base classes


## Installation

```
composer require gozoro/yii2-base
```

## Usage

Usage base controller.

```php

class YourController extends \gozoro\base\web\Controller
{
	// HERE YOUR CODE
}

```

Configuration base Request. 

```php
    'components' => [

        'request' => [
			'class' => 'gozoro\base\web\Request',
        
        ],
	],
```