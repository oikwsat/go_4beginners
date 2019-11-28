# はじめてのGo―シンプルな言語仕様，型システム，並行処理

## 第1章　Go言語の特徴と環境構築―Googleが作った新言語

```sh
# 実行
$ go run hello.go
Hello World!
# コンパイル
$ go build hello.go
$ ls
hello hello.go
$ ./hello
Hello World!
# フォーマット
$ go fmt hello.go
# ドキュメント
$ godoc fmt
$ godoc -http=":3000"
```