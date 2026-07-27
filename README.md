# library-new-arrivals-feed

大阪市立図書館の新着資料一覧を RSS 2.0 として配信するための、生成物だけを置くリポジトリ。

| フィード | 対象 |
|---|---|
| [`computer.xml`](computer.xml) | コンピュータ・情報学（ジャンルコード 11） |

購読URL: `https://koroha568.github.io/library-new-arrivals-feed/computer.xml`

- 1日1回更新。新しく一覧に現れた資料が上、同じ日の中では出版年月の新しい順
- 各項目は蔵書検索システムの詳細ページへリンクする
- 元データは[大阪市立図書館 蔵書検索・予約システム](https://www.oml.city.osaka.lg.jp/licsxp-opac/WOpacMsgNewMenuDispAction.do)の公開情報。取得は1日1リクエスト
- 生成コードは別リポジトリにあり、ここには生成物のみを置く

図書館とは無関係の個人的な仕組みで、公式のものではありません。
