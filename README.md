yii2-categories
Categories

Installation

The preferred way to install this extension is through composer.

Either run

php composer.phar require "giicms/yii2-categories" "dev-master"
or add

"giicms/yii2-categories": "dev-master"
to the require section of your application's composer.json file.

Usage Example

 'modules' => [
        'categories' => [
            'class' => 'giicms\category\Module',
        ],
  ],
