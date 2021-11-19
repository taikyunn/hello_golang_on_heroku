herokuにてHelloworldを返すことができた。

やり方

1.Govendorのインストール
go get -u github.com/kardianos/govendor

公式だと現在は使うなと書いてある。。go mod

2.main.go作成

3.govendor init コマンドを実行
以下のようになるはず。
├── main.go
└── vendor
    └── vendor.json

4.heroku create

5.git push heroku main
