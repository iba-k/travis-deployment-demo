# travis-deployment-demo

[![Build Status](https://travis-ci.org/miya0001/travis-deployment-demo.svg?branch=master)](https://travis-ci.org/miya0001/travis-deployment-demo)

`master`ブランチで変更があると以下のタスクを[Travis CI](https://travis-ci.org/)上で自動的に実行して`gh-pages`にデプロイします。

* CSVファイルをJSONに変更
* JSONが問題なく生成されているかを確認
* `gh-pages`ブランチに`push`

デプロイ後のサイトは以下のように確認できます。

https://miya0001.github.io/travis-deployment-demo
