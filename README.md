# 開発環境の立ち上げ
## 1,設定ファイル(.env)を生成する
```bash
cp /.env.example /.env
```

## 2,dockerイメージを生成する
```bash
docker-compose build
```

## 3,dockerコンテナを起動する
```bash
docker-compose up -d
```