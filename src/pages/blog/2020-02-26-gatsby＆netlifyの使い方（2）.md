---
templateKey: blog-post
title: Gatsby＆Netlifyの使い方（2）
date: 2020-02-26T15:57:48.988Z
description: このブログ用意の段階メモ
featuredpost: true
featuredimage: /img/netlify-github-009.png
tags:
  - やってみた
---
こちらのサイトを参考にしました。

[Github +Gatsby + Netlify CMS で個人ブログを公開する](https://qiita.com/Kento75/items/7316dd5b7a8014d6c178)[](https://qiita.com/Kento75/items/7316dd5b7a8014d6c178)

**ローカルでの動作確認**

まずgit からテンプレートをクローンして準備をします

`$git clone <githubのURL>`

その後、npmの用意をして動かします（npm install + start）

この状態で`localhost:8000`につないでローカル環境での動作を確認します。

問題なければ、今度は自分のgithubにアップしていきます。

**git hubへアップ**

もともと入っていた.gitファイルを削除します。（`rm -rf .git`）

新しくgit設定ファイルを作ります(git init + git remote add origin git@\~\~~)

設定ファイルができたらGithubにpushします。（git add .+ git commit + git push  ）

これで自分のGithubにコードがアップされました。

この後はNetlifyの設定をしていきます。
