# Custom fields for Yii2

This extension for yii framework 2 allows to attach custom field for any ActiveRecord model.

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require --prefer-dist yiister/yii2-custom-field
```

or add

```json
"yiister/yii2-custom-field": "dev-master"
```

to the `require` section of your composer.json.

## Post-installation

Go to the directory with your yii console bootstrap file and execute

```
./yii migrate --migrationPath=@yiister/cf/migrations
```
