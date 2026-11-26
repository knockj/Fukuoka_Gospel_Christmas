# 福岡ゴスペルクリスマス2026 公式サイト

2026年12月19日（土）西南コミュニティセンターで開催する「福岡ゴスペルクリスマス」の公式サイトです。
HTML 1ファイルと画像だけで動く静的サイトなので、GitHub Pages でそのまま公開できます。

## ファイル構成

```
index.html        … サイト本体（CSS・JSもこの中）
favicon.svg       … ブラウザのタブに出るアイコン
.nojekyll         … GitHub Pages の自動変換を止めるための空ファイル
img/
  hero-tree.jpg   … トップの背景
  nagai.jpg / matsuura.jpg / tsuguru.jpg / miyone.jpg / matsuo.jpg … 出演者写真
  team.jpg        … 「歩み」セクションの写真（手を振る実行委員のメンバー）
  flyer.jpg       … チラシ表面
  ogp.jpg         … SNS・LINEでシェアしたときのサムネイル（1200×630）
  apple-touch-icon.png … スマホのホーム画面アイコン
```

## GitHub Pages で公開する手順

1. GitHub で新しいリポジトリを作成（このサイトは `Fukuoka_Gospel_Christmas`、公開設定は **Public**）
2. 「Add file」→「Upload files」から、このフォルダの中身をすべてドラッグ＆ドロップして「Commit changes」
   - `.nojekyll` は隠しファイルなので、見えない場合はなくても動きます
3. リポジトリの「Settings」→「Pages」を開く
4. 「Build and deployment」の Source を **Deploy from a branch**、Branch を **main / (root)** にして「Save」
5. 1〜2分後、https://knockj.github.io/Fukuoka_Gospel_Christmas/ で公開されます

## 公開URL

https://knockj.github.io/Fukuoka_Gospel_Christmas/

LINE や Instagram でシェアしたときのサムネイル（`img/ogp.jpg`）も、このURLで設定済みです。
リポジトリ名を `Fukuoka_Gospel_Christmas` から変える場合は、`index.html` 上部の `og:url` と `og:image` の2か所も合わせて変更してください。

## よく変える場所

| 変えたい内容 | `index.html` で検索する文字 |
| --- | --- |
| チケット申込フォームのURL | `forms.gle` |
| チケット料金 | `id="ticket"` |
| 当日の流れ | `id="program"` |
| 準備の歩み（路上ゴスペルなど） | `id="journey"` |
| よくある質問 | `id="faq"` |
| 出演者の写真 | `img/` の同じファイル名で上書き |

## 公開前の確認事項

- 小学生まで無料／中学生から学生料金（1,000円）で確定か
- お支払い方法の記載（現在は「フォームの案内をご確認ください」のみ）
- フィナーレのキャンドルサービス（11/21 仮案ベース）
- 駐車場の有無（現在は「公共交通機関で」とだけ記載）

企画：Fukuoka Gospel Christmas ｜ Instagram [@gospelchristmasfukuoka26](https://www.instagram.com/gospelchristmasfukuoka26/)
