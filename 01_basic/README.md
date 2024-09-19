# basic

このディレクトリでは，dockerのビルドからコンテナの作成，実行までの基本的な使い方を学びます。

**注意**：このディレクトリの練習は，Docker Desktopをインストールしていることを前提としています。

## 手順

### 0. このディレクトリに移動する

```bash
cd 01_basic
```

### 1. Dockerイメージを作成する

```bash
docker build -t my-python-app .
```

### 2. Dockerコンテナを作成する

```bash
docker run -it --name my-python-app my-python-app
```

ここで，ターミナルで`Hello, World!`と表示されれば成功です。

### 3. Dockerコンテナを停止する

```bash
docker stop my-python-app
```

### 4. Dockerコンテナを削除する

```bash
docker rm my-python-app
```

### 5. Dockerイメージを削除する

```bash
docker rmi my-python-app
```


## 解説

- `docker build`：Dockerイメージを作成するコマンドです。`-t`オプションでイメージ名を指定します。
  - ここで，`docker images`というコマンドをターミナルで実行すると，作成したDockerイメージが表示されます。
- `docker run`：Dockerコンテナを作成して実行するコマンドです。`-it`オプションで対話モードを有効にし，`--name`オプションでコンテナ名を指定します。
  - ここで，`docker ps`というコマンドをターミナルで実行すると，実行中のDockerコンテナが表示されます。
- `docker stop`：実行中のDockerコンテナを停止するコマンドです。
  - ここで，`docker ps`というコマンドをターミナルで実行すると，停止したDockerコンテナが表示されなくなります。
  - また，`docker ps -a`というコマンドをターミナルで実行すると，停止したDockerコンテナも表示されます。
- `docker rm`：Dockerコンテナを削除するコマンドです。
  - ここで，`docker ps -a`というコマンドをターミナルで実行すると，削除したDockerコンテナが表示されなくなります。
- `docker rmi`：Dockerイメージを削除するコマンドです。
  - ここで，`docker images`というコマンドをターミナルで実行すると，削除したDockerイメージが表示されなくなります。
