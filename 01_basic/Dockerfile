# ベースイメージを指定
FROM python:3.9-slim

# 作業ディレクトリを設定
WORKDIR /app

# 依存関係をコピー
COPY requirements.txt .

# 依存関係をインストール
RUN pip install -r requirements.txt

# アプリケーションのソースコードをコピー
COPY . .

# コンテナ起動時に実行されるコマンドを指定
CMD ["python", "hello.py"]
