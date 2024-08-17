## インストール手順
1. Docker と Docker Compose がインストールされていることを確認する。
2. [sns-udemy-infra](https://github.com/budou114/sns-udemy-infra)の環境構築が完了していることを確認する。
3. [sns-udemy-api](https://github.com/budou114/sns-udemy-api)の環境構築が完了していることを確認する。
4. リポジトリをクローンまたはダウンロードする。
5. .env.exampleをコピーして、.envのファイルを作り編集する。
```
NEXT_PUBLIC_API_BASEURL="http://localhost:5050/api"  # APIのURLを設定する
```
6. ルートディレクトリで下記コマンドを実行する。
```
# 依存関係のインストールを実行する。
npm install

# サーバーを起動する。
npm run dev
```
