---
templateKey: blog-post
title: Gatsby Tutorial（2）
date: 2020-03-14T14:18:51.332Z
description: Gatsby
featuredpost: true
featuredimage: /img/netlify-github-009.png
tags:
  - やってみた
---
CSSについて

```
import "./src/styles/global.css"
// or:
// require('./src/styles/global.css')
```
こんな感じでCSSを読み込むんで以下のように記述する

```
import containerStyles from "./container.module.css"
...
<div className={containerStyles.container}>{children}</div>
```
```
.container {
  margin: 3rem auto;
  max-width: 600px;
}
```

こんな感じでpropsとstyleが組み合わさることもある
```
  <div className={styles.user}>
    <img src={props.avatar} className={styles.avatar} alt="" />
    <div className={styles.description}>
      <h2 className={styles.username}>{props.username}</h2>
      <p className={styles.excerpt}>{props.excerpt}</p>
    </div>
  </div>
```

CSS-IN-JSを使いたいなら色々あるよ（参照 https://www.gatsbyjs.org/docs/styling/）
