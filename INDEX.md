# 入口ページ（原稿）

サイトの入口（https://omakeworks.github.io/foldex-site/）に出すページの原本。
公開用の HTML は `tools/make_store_pages.py` が `docs/store/index.html` に生成する。
Partner Center の「Web サイト」欄に入れるのは、このページの URL（2026-10-16 決定）。

> 見た目は tools/make_store_pages.py の build_index（専用レイアウト）。omake works の動画プレイヤー
> （waffleplayer-site・sandplayer-site）の入口ページと同じ作り（2026-10-19、ユーザーの指示）。
> 画像は docs/store/images/index/（アイコン 3 つと、hero_ja.webp・hero_en.webp）。大きな画像は
> `python tools\usage_shots.py ja` / `en` が撮る（印なし）。紹介文の最初の 1 文が大きく出る。
> 書き方の決まり：紹介文 → リンクの一覧（先頭の「使い方」が目立つカードになる）→ **見出し** と
> 「アプリ名 — 説明 [リンク]」の一覧 → 最後の 2 行（不具合の一文・お問い合わせ）。
> 中身は、ストアの掲載文（`tools/store_listing.py`）と README に書いてある事実に合わせる。
> ほかのアプリの説明は、それぞれの入口ページの文に合わせてある。向こうが変わったら合わせる。
> ストアで公開されたら、製品ページへのリンクを足すこと（例: [Microsoft Store で見る](https://apps.microsoft.com/detail/<商品ID>)）。
> 「使い方」（usage.html・usage_en.html）の原本は docs/store/USAGE.md・USAGE_EN.md（画像は tools/usage_shots.py）。

---

## Foldex

Windows の「開く」「保存」ダイアログのすぐ下に、最近使ったフォルダとお気に入りを表示し、クリックするだけでダイアログをそのフォルダへ移動できるツール。使ったフォルダの自動記録、色分けしたグループでのお気に入りの整理、同じ階層の別のフォルダへの移動、ダイアログの外でも使える Foldex ウィンドウに対応。通知領域（タスクトレイ）に常駐して、ダイアログが開いたことを検知します。データは外部に送りません。30 日間、機能制限なしで無料で試せます。

- [使い方](usage.html)
- [プライバシーポリシー](privacy.html)
- [特定商取引法に基づく表示](tokushoho.html)

**omake works のほかのアプリ**

- Waffle Player — 複数の動画や画像をタイル状に並べて、同時に再生・比較できる動画プレイヤーです。 [Waffle Player のページ](https://omakeworks.github.io/waffleplayer-site/)
- Sand Player — 2 本の動画や画像を左右に並べ、差分と半透明の重ね合わせで違いを見つける比較用プレイヤーです。 [Sand Player のページ](https://omakeworks.github.io/sandplayer-site/)

不具合を見つけたら、ご連絡いただけるとうれしいです。改善に役立てます。

お問い合わせ: {{CONTACT_EMAIL}}

---

## Foldex

Shows your recent and favorite folders right below every Windows Open and Save dialog, so one click takes the dialog there. Automatic folder history, color-coded groups for your favorites, jumps to sibling folders, and a Foldex Window you can use without a dialog. Foldex runs in the notification area to detect when a dialog opens. Nothing leaves your PC. Free 30-day trial, all features.

- [How to use](usage_en.html)
- [Privacy Policy](privacy.html)
- [Legal notice (Japan)](tokushoho.html)

**More from omake works**

- Waffle Player — Play and compare multiple videos and images side by side in a tiled grid, all in sync. [Waffle Player](https://omakeworks.github.io/waffleplayer-site/)
- Sand Player — Compare two videos or images side by side with difference and blend views. [Sand Player](https://omakeworks.github.io/sandplayer-site/)

If you find a bug, we'd be glad to hear about it — it helps us improve Foldex.

Contact: {{CONTACT_EMAIL}}
