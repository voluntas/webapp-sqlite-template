# webapp-sqlite-template

## モチベーション

- 自分がよく使う構成をまとめている
- 自分が使いたい技術を使ってる構成

## 今後

- [ ] Litestream 追加

## webapp

- データベースに SQLite を利用
- こちらは参考程度でメンテナンスはあまり頑張っていません
- データベースに TimescaleDB を利用している版はこちら
    - https://github.com/voluntas/webapp-template

```
go 1.19

require (
	github.com/go-playground/validator/v10 v10.11.1
	github.com/goccy/go-yaml v1.9.5
	github.com/golang-migrate/migrate/v4 v4.15.2
	github.com/labstack/echo-contrib v0.13.0
	github.com/labstack/echo/v4 v4.9.0
	github.com/mattn/go-sqlite3 v1.14.15
	github.com/rs/zerolog v1.28.0
	github.com/shiguredo/lumberjack/v3 v3.0.0
	golang.org/x/sync v0.0.0-20220907140024-f12130a52804
)
```


## LICENSE


```
Copyright 2022-2022, voluntas

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
