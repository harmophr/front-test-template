# 環境構築など
## インストールする
`yarn` or `npm i`

## 起動する
`yarn start` or `npm run start`

## 静的解析を使用する
`yarn fix` or `npm run fix`

# テストでの提出について
1. track上での作業
index.htmlについて下記に修正をしてください。
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

2. ビルドする
`yarn build` or `npm run build`

3. buildされたファイルをtrack上にコピーする
ビルド後に`static`ディレクトリ配下に生成される<br>
`css/main.xxxxxxxx.css` を `style.css`に<br>
`js/main.xxxxxxxx.js` を `index.js`にコピーしてください。
