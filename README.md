# 質問まとめページ

受講生（ママさん）向けの Q&A まとめページ。
Discordでの質問と、対談・Zoomで出た質問を格納していく場所。

## 公開URL（受講生に共有するのはこちら）

**https://yu1020ti-arch.github.io/camera-school-qa/**

GitHub Pages（リポジトリ: yu1020ti-arch/camera-school-qa・公開）でホスティング。

## 更新方法

**`data.js` だけ編集すればOK**（`index.html` は触らない）。

- Q&Aの追加 → `QA_LIST` に `{ ... },` のかたまりをコピーして追記（上が新しい）
- `category` は会員サイトの章立てに対応（`"ch1"`〜`"ch10"`、詳細はdata.js冒頭のコメント）
- `source` は `"discord"`（Discord）か `"talk"`（対談・Zoom）
- `topic` は自由記入のラベル（「シャッタースピード」など）。省略OK
- ページ上部の文章は `SITE` を編集

編集後、公開ページに反映するには：

```
cd "このフォルダ"
git add -A && git commit -m "Q&A追加" && git push
```

→ 1〜2分でURLに自動反映されます。

※現在入っている7件はデザイン確認用の仮データ。実データが入ったら差し替える。

## カテゴリーの元ネタ

会員用Notion「忙しいママでも大丈夫！ゼロから始める"我が子フォト"講座」の
会員サイト構成（1章〜10章）に合わせている。

## ローカルで見る

```
cd "このフォルダ" && python3 -m http.server 8941
```

→ http://localhost:8941

## 型にした過去制作物

`Projects/camera-ai-school-hp`（data.jsのみ編集方式）
