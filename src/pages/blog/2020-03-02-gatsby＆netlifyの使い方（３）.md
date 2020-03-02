---
templateKey: blog-post
title: Gatsby＆Netlifyの使い方（３）
date: 2020-02-27T17:03:00.000Z
description: ３つめ
featuredpost: true
featuredimage: /img/netlify-github-009.png
tags:
  - やってみた
---
Netlifyの設定をしていきます。

ログインしたら、サイト公開するGihubリポジトリとの連携、Pull,Push Requestを設定します。

* 「New Site from Git」ボタンを聞く
* Git providerを選ぶ箇所で「GitHub」を選ぶ
* 対象のリポジゴリを偉ぶため「only select repositories」にチェック。
* 使っているブランチを選択
* その後「Deploy site」をクリック
* デプロイ(サーバーにアップロードして使える状態にすること)できたらサイト表示
* ホーム画面の「Domain settings」からURLを変更



管理者画面へのログインするための設定を行う。

Setting→Identity→Enable Git GateWayをクリック

するとサイト名/admin のログイン画面で入れるようになる
