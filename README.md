# Dockerを学ぶためのリポジトリ

## 練習
各フォルダに練習用のファイルがあります
各フォルダの`README.md`を参照してください

- [Dockerの基本的な使い方](./01_basic/README.md)
- [サーバーとの通信方法](./02_serverContainer/README.md)
- [起動したコンテナに入る方法](./03_operateContainer/README.md)
- [マウント・ボリュームなどデータの扱い方](./04_data/README.md)


## Dockerとは

Dockerは、コンテナ型の仮想化技術を提供するプラットフォームです。Dockerを使うことで、アプリケーションを簡単に開発、デプロイ、実行することができます。

## Dockerの特徴

Dockerの特徴は以下の通りです。

- **軽量**：Dockerは、Linuxのカーネル機能を利用してコンテナを作成するため、仮想マシンに比べて軽量です。
- **高速**：Dockerは、コンテナを作成するためのレイヤーを再利用することができるため、高速にコンテナを作成することができます。
- **環境の再現性**：Dockerは、コンテナをイメージとして保存することができるため、環境の再現性が高いです。
- **スケーラビリティ**：Dockerは、コンテナを複数のホストで実行することができるため、スケーラビリティが高いです。

## Dockerの基本的な使い方

Dockerの基本的な使い方は以下の通りです。

1. Dockerイメージを作成する
2. Dockerコンテナを作成する
3. Dockerコンテナを実行する

## Dockerのインストール方法

Dockerをインストールする方法は、以下の通りです。

1. [Docker Desktop](https://www.docker.com/products/docker-desktop)をダウンロードする
2. ダウンロードしたファイルを実行してインストールする
3. インストールが完了したら、Docker Desktopを起動する

## Dockerのコマンド

Dockerを使う際によく使うコマンドは以下の通りです。

- `docker build`：Dockerイメージを作成する
- `docker run`：Dockerコンテナを作成して実行する
- `docker ps`：実行中のDockerコンテナを表示する
- `docker stop`：実行中のDockerコンテナを停止する
- `docker rm`：Dockerコンテナを削除する
- `docker rmi`：Dockerイメージを削除する

## まとめ

Dockerは、コンテナ型の仮想化技術を提供するプラットフォームであり、軽量、高速、環境の再現性が高い、スケーラビリティが高いという特徴があります。Dockerを使うことで、アプリケーションを簡単に開発、デプロイ、実行することができます。
