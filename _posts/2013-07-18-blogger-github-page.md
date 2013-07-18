---
layout: post
title: "ドラクエのリハビリに Blogger から Github Page にブログ移行したった"
description: ""
category: 
tags: []
date: 2013-07-18 17:16
---
{% include JB/setup %}

廃人フレンドに「おまえ最近めっちゃ IN してね？」と言われ目から大きなうろこが落ちました。

ほんとにねえ、まさか自分が MMO にハマるとはねえ。

特に最近はですね、ゲーム内経済が空前の好景気に見舞われていてですね、後発参入組な自分としては先行廃ゲーマーに追いつくチャンスなのです。楽しいのです。

　

ライトユーザでも定期的かつ安定的な収入を得る手段が実装されたために、ゲーム内全体の可処分所得が増大してるんですよね。

当然、廃ゲーマー層はこのバブルにのりこめーっと武器・防具をガシガシと作りますので、武器・防具の材料の需給バランスが軒並み需要不足となりまして価格が高騰して、この高騰した価格はこれまたライト層の収入となりますので、原材料費につられ高くなった武器・防具もこれまた売れて廃人層はますますウマー、とね。

ああ、回る経済とはこういうものなんだ、かつて高度経済成長期と呼ばれた頃のわが国日本もこのような様相であったのかなと思うと胸が熱くなるよね、といった話を美容師さんにしたら「それよりも LINE POP の方がおもしろいですよ」と LINE POP の話が始まってしまいました。もっとドラクエの話がしたかったのに。

 　

ゲーム内のコミュニケーションもですねえ。

齢も仕事も違うけどもドラクエという前提が共有されているという不思議な距離感がすごく心地いいんですよね。

とりあえずまぁ、MMO やったことない奴らはドラクエ10やってみろ。入門にはいいと思うぞ。ソースはおれだ。

　

#### 移行にあたり参考にしたページ

+ Jekyll-Bootstrap のローカル環境のセットアップ
	+ [Blogging with Jekyll Tutorial | Jekyll-Bootstrap](http://jekyllbootstrap.com/)
+ Github Pages の Jekyll の設定とローカルの設定とを合わせる
	+ [Using Jekyll with Pages | GitHub Help](https://help.github.com/articles/using-jekyll-with-pages)
+ 旧ブログからのエントリの移行
	+ [Blog migrations](http://jekyllrb.com/docs/migrations/)
		+ サイト内でリンクされてる [@ngauthier](https://github.com/ngauthier) の [スクリプト](https://gist.github.com/ngauthier/1506614) を使用しました。
			+ ちょこっとだけ[パッチあてました](https://gist.github.com/amazedkoumei/6027433)
				+ 旧エントリURLが一部(タイトルに数字が含まれる場合/タイトルに英数字が全く含まれない場合)間違って取得されていたので修正
				+ コメントを日時の昇順から降順に変更
				+ 旧エントリの label を取得するように変更
+ Jekyll-Bootstrap の Theme の編集
	+ Theme "Twitter" が同梱されているのでそれを参考にオリジナルの Theme を作成しました
		+ Theme ファイルは HTML + CSS をベースに + Jekyll固有の if文, for文, 変数 というニュアンス
			+ Wordpress の Theme の編集と比べると Wordpress が生 PHP な分、Jekyll のが楽な印象
			+ Blogger の Theme の編集と比べると固有な文法が Blogger が XML like, Jekyll が Ruby like なため Jekyll の方が楽な印象
			+ Jekyll固有の変数についてはこのページを参照しました
				+ [Variables](http://jekyllrb.com/docs/variables/)
+ カスタムドメインの設定
	+ [Setting up a custom domain with Pages | GitHub Help](https://help.github.com/articles/setting-up-a-custom-domain-with-pages)

　

#### このページ (blog.amazedkoumei.com) のソースコード

こちらになります。

+ [amazedkoumei/amazedkoumei.github.com](https://github.com/amazedkoumei/amazedkoumei.github.com)

　

#### TODO

画像がねえ・・Blogger にホスティングされたままなんですよねえ・・実は・・


以上です！

　
