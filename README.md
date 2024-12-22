# Open API docsを書いてみる

1. Open API ymlを書く
2. ymlからGoのコードを生成する
3. 生成したコードに肉付け実装をする

ところまでやってみるリポジトリ

# コード生成

```
go mod tidy
go generate ./...
go run cmd/api/main.go
```

# 超参考

- [[OpenAPI] Go言語でAPIファーストな開発をしてみた - oapi-codegen実践編](https://zenn.dev/kama_meshi/articles/e11d5c5842e5e2)