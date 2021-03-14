# Promcode

### 開発環境
・ macOS Catalina 10.15.6  
・ Vue CLI 3.10.0  
・ Neo4j Desktop 1.2.9  
・ Node.js 10.14.1

### 作業手順
#### Neo4jの起動と初期化
```
1. Neo4j Desktop起動
2. PROMCODE DBを起動
3. DBに対し, CALL n10s.graphconfig.init()を実行 (n10sでのグラフの初期化)
```
#### PROMCODE-serverの起動
```
$ cd PROMCODE-server
$ node app.js
```

#### PROMCODE-clientのローカルサーバ起動
```
$ cd PROMCODE-client
$ npm run serve
```

#### TurtleファイルのPOST
```
1. ブラウザでhttp://localhost:8080にアクセス
2. ファイル選択でPOSTするTurtleファイルを選択
3. 送信ボタンを押下
```
