sinatra-template
================

Sinatra with Slim, Unicorn, RSpec, Capistrano 3 and Provisioning tool


## インストール
1. Repositoryをcloneする

        git clone https://github.com/ohtacaesar/sinatra-template.git project_name

2. cloneしたプロジェクトのディレクトリに入る

        cd project_name

3. bundleでライブラリを導入する

        bundle install --path=vendor/bundle

## 起動（テスト用）

    bundle exec unicorn
