# organizational-hierarchy
RDF description of organizational hierarchy of Sakai-city

## ソース
- [組織図](https://www.city.fukui-sakai.lg.jp/somu/shisei/gaiyo/soshiki/documents/sosikizu20210401.pdf)
- ネットワーク図の生成は[神崎さんのツール](https://www.kanzaki.com/works/2009/pub/graph-draw)を使わせてもらっています。 
  - 全部のネットワーク graph-draw.png

## 作業と課題
- [semantic-digital-agency](https://github.com/takechan2000/semantic-digital-agency)を参考に、坂井市の組織図を記述してみました。こちらの[動画](https://www.youtube.com/watch?v=lllX8TGA5ck)も参考にしてます。
- 人名はありません。
- ()内のラベルはskos:prefLabelを二つつけているが、これで良いのか？
- 市長から線が伸びていない「議会」等は「坂井市」のsubOrganizationなのか？現在は、org:reportsToをつけずにおいている。
- 点線は何を表しているのか？