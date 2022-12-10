## git init 後 composer.json を作成

中身

```
{
    "require": {
        "monolog/monolog": "1.0.*"
    }
}

```

アプリで使うライブラリを追記今回は monolog

## $ composer install

`$ composer install` を実行

`vendor` フォルダが作成される

vendor/composer
vendor/monolog
vendor/autoload.php

### autoload.php

composer で追加したライブラリを読み込む処理
アプリで使うときは `require_once("vendor/autoload.php");` をする

