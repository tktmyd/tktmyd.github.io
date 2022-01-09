# Memo

## 使えるようにするまで
```
$ brew install python3
$ pip3 install mkdocs
$ pip3 install mkdocs-material
$ pip3 install fontawesome-markdown
```

## 設定ファイル
`.htaccess` は保存できない．

`mkdocs build`したあとに無理矢理保存することはできるが，デフォルトだと次の `build` で削除される．

`mkdocs build --dirty`というオプションで回避できるが，`dirty`の付け忘れで削除されるのでは秘密情報のアップロード先として危険．

サーバにだけ置いておいて `rsync` で`--delete`しない？
ゴミを消すときに全部消える．

別にスクリプトを書いて，そこで`.htaccess`をコピーする？
... これが一番現実的か．

## 図の配置

`aaaa.md`というのに対して
`aaaa/fig.png`を用いると，`site`では両方が同じ`aaaa`ディレクトリに格納されて都合が良い．

