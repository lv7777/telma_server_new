# telma-server

telmaの鯖側をsubmoduleとする。

# directory

* main.js

すべてのroot. webpack entry point.

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

## moduleの結合

* webpack

ただclientじゃないんだしほんとにこれいる？

## taskrunner

* gulp

## lint系

* eslint

めっちゃ大事。