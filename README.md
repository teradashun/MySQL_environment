# MySQL学習環境

## 起動方法
1. Docker Desktopを起動
2. `docker compose up -d`

## コンテナ起動後、MySQLへの接続方法
docker exec -it mysql-container mysql -u root -p

## 接続情報
- ホスト: localhost
- ポート: 3306
- ユーザー: root / [設定したパスワード]