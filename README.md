# Node.js環境構築

- node.jsの環境です。これ単体で使うことはないと思いますが、手軽にサーバー環境を試したいときなどに使ってください。

- dockerを使ったnodeの環境構築なのでnodockと名付けています。


## NoDock

1. リポジトリをクローン

   ```
   git clone https://gitlab.com/welcome-to-sodai/node.git node_app/nodock
   ```

2. nodockの階層で

   ```
   docker-compose up -d node
   ```

3. [ここに](http://localhost:3000)アクセスし、うまくいっているか確認


## 使い方

- 始めるとき nodockの階層で
   ```bash
   docker-compose up -d node
   ```
- 終わるとき
   ```bash
   docker-compose down
   ```

## まとめ

- Node.jsの環境構築ができた

## Next Step

- node.jsで手軽にfirebaseを試したいときとかに使うのかな

   
