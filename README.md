# 概要
DockerコンテナでPostgreSQL環境を構築します。

# 環境変数
`.env.sample`を複製し、`.env`を作成します。

# コンテナ起動
DockerコンテナでPostgreSQLを起動します。
```bash
docker-compose up
```
# コンテナの永続化
DBのデータディレクトリは`./db`にマウントされます。