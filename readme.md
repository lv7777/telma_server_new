# telma-server

telmaの鯖側をsubmoduleとする。

# directory

* main.js

~~~すべてのroot. entry point.~~~

warning:現在express.jsがサーバーを起動するファイルとなっています。

* express.js

expressサーバーを起動する。ルーティングやsqlの処理等はいろんなjsファイルに投げている。

* router.js

expressを使ってルーティング関係を操る。

* socketio.js

socketioを使ってwebsocket通信を担当する。

鯖を立てる必要が有るためexpress.jsに依存？

* sql.js

を使ってmysqlとの通信を担当する。 

# 使用予定フレームワーク

## test

* mocha

* super

## moduleの結合

* webpack

ただclientじゃないんだしほんとにこれいる？

## taskrunner

* gulp

## lint系

* eslint

めっちゃ大事。

## 認証系

* passport

* passport-twitter

# express middleware

* body-perser

postを受け取るときに絶対必要。これがないとパラメータを受け取れない。

## その他

jsdoc(api書くようのいいのがあったらそっち使う。


# このプロジェクトの進め方・心構え等

github flowの派生版。

基本的にはmaster branchで行う。

ただしバグ修正のみブランチを切る。ブランチ名にはissue numberを含めること。

# contributing

`npm install`