# AIDG Legal Pages

`UNSCRIPTED AI DEATH GAME -Prompt to Kill-` の公開用法務ページ置き場。

## 公開URL

プライバシーポリシー:

```text
https://3457457547.github.io/aidg-legal/privacy-policy.html
```

画像の利用条件（日本語・英語・簡体字・繁体字・韓国語）:

```text
https://3457457547.github.io/aidg-legal/image-use-terms.html
```

画像の利用条件はカスタムキャラクターの画像機能だけを対象にした文書。
Steamの独自EULA登録や同意取得を示すものではない。プライバシーポリシーと相互リンクする。

## ファイル

| ファイル | 用途 |
|---|---|
| `privacy-policy.html` | Steamworks の Privacy Policy URL に入力する公開ページ |
| `image-use-terms.html` | カスタムキャラクターの画像利用条件 |
| `.nojekyll` | GitHub Pages で余計なJekyll処理を避けるための空ファイル |

## 更新手順

1. メインプロジェクト側の `ai-death-game-desktop/docs/privacy-policy.md` または `image-use-terms.md` を更新する。
2. メインプロジェクトルートで `python release_work/2026-10-01-f08-static/render-legal-pages.py` を実行し、同内容のHTMLを `docs/` とこのリポジトリへ生成する。
3. 原稿・HTMLの全文と差分、相互リンク、条件文の一致を検査する。
4. このリポジトリ内の対象ファイルだけを commit / push する。
5. 公開URLを取得し、HTTP 200と公開本文の一致を確認する。
