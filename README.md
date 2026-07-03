# 質問まとめページ

受講生（ママさん）向けの Q&A まとめページ。
Discordでの質問と、対談・Zoomで出た質問を格納していく場所。

## 更新方法

**`data.js` だけ編集すればOK**（`index.html` は触らない）。

- Q&Aの追加 → `QA_LIST` に `{ ... },` のかたまりをコピーして追記（上が新しい）
- `category` は `"discord"`（Discord）か `"talk"`（対談・Zoom）の2区分
- `topic` は自由記入のラベル（「カメラ設定」など）。省略OK
- ページ上部の文章は `SITE` を編集

※現在入っている5件はデザイン確認用の仮データ。実データが入ったら差し替える。

## ローカルで見る

```
cd "このフォルダ" && python3 -m http.server 8941
```

→ http://localhost:8941

## 型にした過去制作物

`Projects/camera-ai-school-hp`（data.jsのみ編集方式）
