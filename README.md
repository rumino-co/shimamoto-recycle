# 嶋本建設株式会社リサイクルセンター | 公式サイト

熊本県上益城郡益城町の産業廃棄物中間処理施設「嶋本建設株式会社リサイクルセンター」の公式ホームページです。

## 公開URL

https://rumino-co.github.io/shimamoto-recycle/

## 構成

静的HTML/CSS/JSのみで構成されています。ビルドツール不要。

```
shimamoto-recycle/
├── index.html          トップ
├── service.html        取扱品目・処理フロー
├── profile.html        会社案内・許可証
├── news.html           お知らせ
├── contact.html        お問い合わせ
├── thanks.html         送信完了(noindex)
├── sitemap.xml
├── robots.txt
├── css/
│   └── style.css       Eco Emerald テーマ
├── js/
│   └── main.js         ハンバーガーメニュー制御
└── images/
    └── logo.svg
```

## ローカルで確認

ブラウザで `index.html` を直接開くか、簡易サーバーを起動します。

```bash
# Python 3 がインストールされている場合
python -m http.server 8000
# → http://localhost:8000 で確認
```

## GitHub Pagesで公開する手順

### 1. 新しいリポジトリを作成

GitHubにログインし、`shimamoto-recycle` という名前で**公開リポジトリ**を新規作成してください。
(Add README / .gitignore / license はすべてオフで構いません)

### 2. ローカルからプッシュ

このHPフォルダ内で以下を実行します。

```bash
cd "G:/マイドライブ/06　会社/嶋本建設リサイクルセンター/HP"
git init
git add .
git commit -m "Initial commit: 嶋本建設リサイクルセンター HP"
git branch -M main
git remote add origin https://github.com/rumino-co/shimamoto-recycle.git
git push -u origin main
```

### 3. GitHub PagesをONにする

1. リポジトリの `Settings` → `Pages`
2. `Build and deployment` の `Source` を `Deploy from a branch` に設定
3. `Branch` を `main` / `/ (root)` に設定して `Save`
4. 数分後、`https://rumino-co.github.io/shimamoto-recycle/` で公開されます

## 関連サイト

- 親会社: 嶋本建設株式会社 https://rumino-co.github.io/

## 会社情報

| 項目 | 内容 |
| --- | --- |
| 会社名 | 嶋本建設株式会社リサイクルセンター |
| 代表者 | 代表取締役　嶋本　稔 |
| 所在地 | 熊本県上益城郡益城町杉堂690番地3 |
| TEL | 096-289-8550 |
| FAX | 096-289-8551 |
| 営業時間 | 8:00～17:00 |

---

&copy; 2026 嶋本建設株式会社リサイクルセンター
