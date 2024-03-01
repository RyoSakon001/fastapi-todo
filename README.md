# 環境構築手順
## Docker環境構築
1. Docker Desktop をインストールしていることを確認
2. VSCodeの拡張機能「Dev Containers」をインストールする
3. `.devcontainer/example.env` をコピーし、同じ階層に `.env`を作成する
4. エディタ左下の `><` をクリック
5. 「コンテナで再度開く」を選択することで、コンテナ作成〜コンテナの中に入る作業をまとめて行ってもらう

## APIサーバー起動
1. コマンド`make upgrade`を実行し、DBの初期化を行う
2. コマンド`make dev`を実行し、Webサーバーを起動
3. `INFO: Application startup complete.` と表示されることを確認
4. http://127.0.0.1:8000/docs にアクセスし、Swaggerドキュメントが表示されることを確認

## 公式ドキュメント等
- [VSCode DevContainer](https://code.visualstudio.com/docs/devcontainers/tutorial)
- [FastAPI](https://fastapi.tiangolo.com/ja/)
- [Makefile](https://zenn.dev/keitean/articles/aaef913b433677)
