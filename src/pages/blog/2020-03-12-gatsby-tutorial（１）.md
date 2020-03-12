---
templateKey: blog-post
title: Gatsby Tutorial（１）
date: 2020-03-03T15:23:26.428Z
description: Gatsby公式チュートリアルやってみた
featuredpost: true
featuredimage: /img/netlify-github-009.png
tags:
  - やってみた
---
<https://www.gatsbyjs.org/tutorial/part-one/>

## １.ブロックビルディングを知る

`/src/pages`　にページのJSファイルが入る。

＊Gatsbyはホットリローディングを使っているので保存するだけで画面が変わる。便利

```import React from "rect"

export default () => (

... (ここにHTMLを書くと画面に表示される)

)
```

＊https://source.unsplash.com/random/400x200  で画像がランダムで表示されて便利。

## 2.コンポーネントを作る
`src/components`フォルダを作成して以下のような形でコンポーネント使える

src/components/~
```
import React from "react"
export default () =>(
...
)
```

src/pages/~
```
import React from "react"
import Header from "../components/header"
export default () =>(
<Header />
...
)
```

props使えば情報渡せる
pages
```
<Header headerText="text">
```
```
<h1>{ props.headerText }<h1>
```

## 3.ページ同士を繋げる（リンク機能）

`import { Link } from "gatsby"`＋
`<Link to="/">home </Link>`
で使える。

## 4.デプロイする
Surge使えってさ。
入れたけどめんどくて使ってない。
