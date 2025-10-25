# SpartanChat

(1)環境変数ファイル(.env)ファイルを作成します

Mac、Windows(PowerShell、Git Bash)の場合
 cp .env.example .env

Windows(コマンドプロンプト)の場合
 copy .env.example .env

(2)起動方法
・イメージのビルド
  docker compose build
docker-compose.ymlの内容に従って、コンテナイメージをビルドします。
初回または依存パッケージを更新したときに実行してください。

・コンテナの起動
　docker compose up
コンテナを起動します。
-dオプションをつけるとバックグラウンドで起動します

