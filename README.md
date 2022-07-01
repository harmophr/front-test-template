# 環境構築など
## インストールする
`yarn` or `npm i`

## 起動する
`yarn start` or `npm run start`

## 静的解析を使用する
`yarn fix` or `npm run fix`

# trackでの動作確認・テストについて
1. track上での作業<br>
index.htmlを下記に修正してください。
```html
<html lang="ja">
  <head>
    <title>メモアプリ</title>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <link href="./style.css" rel="stylesheet">
  </head>
  <body>
    <div id="root"></div>
    <script defer src="index.js"></script>
  </body>
</html>
```

2. ローカルマシンでビルドする<br>
`yarn build` or `npm run build`

3. buildされたファイルをtrack上にコピーする<br>
ビルド後に`static`ディレクトリ配下に生成される<br>
`css/main.xxxxxxxx.css` を `style.css`に<br>
`js/main.xxxxxxxx.js` を `index.js`にコピーしてください。

# ソースコードについて<br>
個人の名前などが特定されないブランチ名でpush後、テスト後のFBにブランチ名を教えてください。
