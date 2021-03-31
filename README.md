# Node.js環境構築

- node.jsの環境です。これ単体で使うことはないと思いますが、手軽にサーバー環境を試したいときなどに使ってください。


## NoDock

1. リポジトリをクローン

   ```
   git clone https://github.com/Sodai-circle/Node.js.git node_app/nodock
   ```

2. nodockの階層で

   ```
   docker-compose up -d node
   ```


## 使い方

- 始めるとき nodockの階層で
   ```bash
   docker-compose up -d node
   ```
- 終わるとき
   ```bash
   docker-compose down
   ```

   
