# Yii2 slider-pro widget

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

To install, either run

```
$ php composer.phar require edofre/yii2-slider-pro "@dev"
```

or add

```
"edofre/yii2-slider-pro": "@dev"
```

to the ```require``` section of your `composer.json` file.

## Usage

```php
<?= \edofre\SliderPro::widget([
        'id' 			=> 'slider-pro',
        'sliderOptions'	=> [
        	'width'		=> 960,
			'height'	=> 500,
			'arrows'	=> true,
        ]
    ]);
?>
```