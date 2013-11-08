fuelphp_setup
=============

FuelPHP 1.7 を新規インストールする際に利用できます。


## How to install

project_name は適宜 読み替えて下さい。

```bash
git clone git@github.com:chatii/fuelphp_setup.git project_name
cd project_name
# 本リポジトリ情報の削除と初期化
rm -rf ./.git/
git init
# Composer の取得
curl -sS https://getcomposer.org/installer | php
# composer.json を元にパッケージのインストール
php composer.phar install
```


## Special Thanks
Recipe は yandod(https://github.com/yandod) さんの
https://github.com/yandod/php5-nginx-vagrant-sample
を参考にさせていただきました。

以前公開した chatii/php5-nginx-vagrant-sample_for_FuelPHP(https://github.com/chatii/php5-nginx-vagrant-sample_for_FuelPHP) とあわせて、厚く御礼申し上げます。