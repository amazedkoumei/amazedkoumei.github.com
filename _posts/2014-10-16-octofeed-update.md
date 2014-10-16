---
layout: post
title: "Octofeed Update"
description: ""
category: 
tags: [octofeed]
date: 2014-10-16 11:20
---
{% include JB/setup %}

1年近く放置してた iPhone アプリ の Octofeed、久しぶりにアップデートしました。

[インストールはこちらから (有料)](https://itunes.apple.com/jp/app/id574223751)

![screenshot1]({{ site.url }}/assets/entry/2014-10-16-screenshot01.png)
![screenshot2]({{ site.url }}/assets/entry/2014-10-16-screenshot02.png)
![screenshot2]({{ site.url }}/assets/entry/2014-10-16-screenshot03.png)


Follow した人や Watch しているリポジトリのアクティビティが流れてくる News feed と Notification をつらつらと眺められるアプリです。
ついでに気になった人を Follow したり、気になったリポジトリに Star つけたり Watch したりできます。


さらについでに README がちょっと読みやすい。

下の画面は [ReviewNinja](https://github.com/reviewninja/review.ninja) の README を表示したところ。
左側が Octofeedで。右側が Mobile Safari。

![README]({{ site.url }}/assets/entry/2014-10-16-screenshot-readme.png)
![README Mobile Safari]({{ site.url }}/assets/entry/2014-10-16-screenshot-readme-safari.png)

あんまかわんないじゃん。なにこれ切ない。


#### 今回バージョンの変更点 その1

片手で扱いやすくなるよう UI を変更してみました。iPhone 大きくなりますし。大きくなりましたし。

このエントリ読んでおもしろいコンセプトだな、と思って真似してみたんですよね。ちなみにこのブログ好きでよく読んでます。iOS アプリで食ってくために色々考えて、色々トライして、その結果を過程も含めて丁寧に書いてくれてる。紹介されてるツールやサイトもおもしろいものが多い。

- [iPhone片手操作に特化した無料の爆速ToDoアプリJetDoを作った | うめブログ](http://umenon.com/2014/08/12/jetdo/)

片手で扱いやすくするために具体的にどう変更したの、というと、いままで Navigation で遷移していた画面を Modal にして、その Modal View の左下に閉じるボタンをつけました。

![これな]({{ site.url }}/assets/entry/2014-10-16-screenshot-readme-korena.png)


片手で扱いやすくするってテーマとして面白そうだし、UI 考えるときのひとつの基準として使えそうだし、工夫の余地もいろいろありそうだなと思いました。


#### 今回バージョンの変更点 その2

News Feed, Notification, Issues の TableViewCell のレイアウトを変更しました。


#### 今回バージョンの変更点 その3

いろいろと bugfix しました。

#### 今回バージョンの変更点 その3

お値段を300円から200円にしました。


以上です。