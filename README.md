# meilisearch-japanese

Meilisearch の 日本語を強制してビルドするリポジトリ

```sh
$ docker pull ghcr.io/naknao-nnct/meilisearch-japanese:1.15
$ docker run -p 7700:7700 -v $(pwd)/meili_data:/meili_data ghcr.io/naknao-nnct/meilisearch-japanese:1.15
```

### 参考文献
* [meilisearch 日本語対応(トーカナイザの強制日本語化)](https://qiita.com/kesuzuki/items/1e9c236bf59082d84655)

