node-red-heroku
================

A wrapper for deploying [Node-RED](http://nodered.org) into the [Heroku](https://www.heroku.com).

### HerokuにNode-REDを導入する
以下の、「Deploy to Heroku」をクリックしましょう。Herokuの無料プランを使って、Node-REDの利用を始めることができます。

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/kolinz/node-red-heroku)

### Node-REDエディタをパスワードで保護しましょう。

Node-REDは、各種APIやセンサー、AI等と連携し、データ処理を行うことができるローコードプラットフォームです。デフォルトでは誰でも操作できるため、ユーザー名とパスワードを設定することを推奨します。

ユーザー定義変数

* NODE_RED_USERNAME - Node-REDにログインする際のユーザー名
* NODE_RED_PASSWORD - Node-REDにログインする際のパスワード

### Node-REDと同時にインストールする追加ノード
ダッシュボード、地図、Teachable Machineによる機械学習モデルの利用、obniz連携(IoT)、LINE API、Slack bot、NoSQLデータベースのApache CouchDB/IBM Cloudantとの連携、IBM Watson APIの呼び出し
- [node-red-dashboard](https://flows.nodered.org/node/node-red-dashboard) : 3.1.7
- [node-red-contrib-ui-upload](https://flows.nodered.org/node/node-red-contrib-ui-upload) : 0.5.2
- [node-red-contrib-web-worldmap](https://flows.nodered.org/node/node-red-contrib-web-worldmap) : 2.28.1
- [node-red-contrib-teachable-machine](https://flows.nodered.org/node/node-red-contrib-teachable-machine) : 1.3.1
- [node-red-contrib-obniz](https://flows.nodered.org/node/node-red-contrib-obniz) : 0.6.2
- [node-red-contrib-node-line-api](https://www.npmjs.com/package/node-red-contrib-node-line-api) : 0.8.5
- [node-red-contrib-line-messaging-api](https://flows.nodered.org/node/node-red-contrib-line-messaging-api) : 0.1.11
- [node-red-contrib-slack](https://flows.nodered.org/node/node-red-contrib-slack) : 2.0.0
- [node-red-contrib-cloudantplus](https://flows.nodered.org/node/node-red-contrib-cloudantplus) : 2.0.4
- [node-red-node-watson](https://flows.nodered.org/node/node-red-node-watson) : 0.10.3

### 参考資料
- Node-RED関連
  - [Node-RED ユーザーガイド](https://nodered.jp/docs/user-guide/) << Getting Startedの「Node-REDをインストールする」は飛ばしてください。
  - [Node-REDの概念](https://nodered.jp/docs/user-guide/concepts) << 用語集のようなもの
  - [Node-RED ドキュメント](https://nodered.jp/docs/)
- Heroku関連
  - [Heroku ドキュメント](https://devcenter.heroku.com/ja/categories/reference)
- Heroku上でNode-REDを起動し、サンプルアプリを作るまでの手順書
  - [講義サポート:HerokuでNode-REDを動かす](https://mydocument.atlassian.net/wiki/spaces/support4textbook/pages/1672609805/Heroku+Node-RED)
 
