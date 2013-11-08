fuelphp_setup
=============

FuelPHP 1.7 を新規インストールする際に利用できます。


## How to install

```bash
git clone git@github.com:chatii/fuelphp_setup.git
# 自分のプロジェクトにするために
mv fuelphp_setup project_name
cd project_name
# 本リポジトリ情報の削除と初期化
rm -rf ./.git/
git init
# Composer の取得
curl -sS https://getcomposer.org/installer | php
# composer.json を元にパッケージのインストール
php composer.phar install
```
