# environment-test
M1 Mac特有の環境構築を学ぶためのファイル群

- m1-pyの方ではcatboostが入らない
- intel-pyの方ではpolarsが実行できない

コマンド群
```
docker-compose up -d
docker-compose exec intel-py bash
docker-compose exec m1-py bash
pip install poetry && poetry config virtualenvs.create false
poetry install
```
