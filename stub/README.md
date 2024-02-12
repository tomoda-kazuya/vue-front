# stubサーバーの使用方法
## 起動方法
stubディレクトリ直下で以下コマンド実行
```
npm run serve
```

apiディレクトリ配下に返したいjsonを配置して、上記コマンドを実行するとローカルのport3010でjson-serverのページが開く。

api配下のjsonファイルのkeyがエンドポイントになる仕様のため、ファイル名とKey名は揃えて管理した方がわかりやすいのでそうしてください。

カスタムルーターがこのバージョンだと使えなくなっているため不便だが、本番環境に切り替えるときにURIを変える必要あり。カスタムルーターの使い方が分かり次第改修予定。

json-serverについては[こちら](https://github.com/typicode/json-server)参照