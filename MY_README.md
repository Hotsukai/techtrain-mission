## メモ
go on dockerだと外部モジュールのコードの補完がうまく行かない

## 起動方法
```sh
# DB起動
$ docker-compose up
# DB接続
$ mysql -u root -p -h localhost -P 3306 --protocol=tcp
# WEB API 起動
$ go run main.go
```