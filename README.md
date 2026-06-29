# AIを活用したPR・SNS運用サポート LP

AIを活用したPR・SNS運用サポートサービスの1ページLPです。  
HTML / CSS / JavaScriptのみで作成しているため、Netlifyでそのまま無料公開できます。

## ファイル構成

```text
LP/
├── index.html
├── style.css
├── script.js
├── README.md
├── images/
│   ├── sample01.jpg
│   ├── sample02.jpg
│   ├── sample03.jpg
│   ├── sample04.jpg
│   └── sample05.jpg
└── originals/
    └── 元画像
```

## 編集方法

- 文章を変更する場合は `index.html` を編集します。
- 色、余白、文字サイズ、レイアウトを変更する場合は `style.css` を編集します。
- メニュー開閉やスクロール時の表示演出は `script.js` にまとめています。
- 画像を差し替える場合は `images/` 内の画像を同じファイル名で置き換えると、HTML側の修正なしで反映できます。

## Netlifyで公開する手順

1. GitHubで新しいリポジトリを作成します。
2. この `LP` フォルダ内のファイル一式をリポジトリにアップロードします。
3. Netlifyにログインします。
4. 「Add new site」から「Import an existing project」を選択します。
5. GitHubを連携し、作成したリポジトリを選択します。
6. Build command は空欄のままでOKです。
7. Publish directory は `.` を指定します。
8. Deployを実行すると公開されます。

## 公開前チェック

- Googleフォームのリンクが正しいか確認してください。
- OGP画像は `images/sample02.jpg` に設定しています。
- 公開URLが決まったら、必要に応じて `index.html` のSEO / OGP欄に `og:url` を追加してください。
- 料金は仮の目安として入れているため、正式な金額に差し替えてください。
