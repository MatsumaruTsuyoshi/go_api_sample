# go_api_sample

[この記事](https://qiita.com/k-penguin-sato/items/8088b69304ee7e8f70be)を参考に動かしてみました。

# 立ち上げ

`
go mod init api
`

`
go mod tidy
`

# 動作確認

`
go run main.go
`

ALL GET

`
curl http://localhost:8000/api/books
`

GET

`
curl http://localhost:8000/api/books/1
`
