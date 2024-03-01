# 環境構築手順
## Docker環境構築
1. VSCodeの拡張機能「Dev Containers」をインストールする
2. `.devcontainer/example.env` をコピーし、同じ階層に `.env`を作成する
3. エディタ左下の `><` をクリック
4. 「コンテナで再度開く」を選択することで、コンテナ作成〜コンテナの中に入る作業をまとめて行ってもらう

## APIサーバー起動
1. コマンド`make dev`を実行
2. `INFO: Application startup complete.` と表示されることを確認
3. http://127.0.0.1:8000/docs にアクセスし、Swaggerドキュメントが表示されることを確認
