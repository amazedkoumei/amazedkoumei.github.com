---
layout: post
title: "Yosemite + iMovie 10.0.6 で App Previews 作った"
description: ""
category: 
tags: [octofeed iPhoneアプリ AppPreviews]
date: 2014-10-18 14:30
---
{% include JB/setup %}

App Previews とは

+ [App Previews - App Store - Apple Developer](https://developer.apple.com/app-store/app-previews/)

iOS8 リリース以降、iPhone, iPad の AppStore でスクリーンショットの1番左側が動画になってるアプリをちょいちょいみかけますが、あれのことです。あれを作成するための素敵な機能が Yosemite で QuickTime Player に追加されました。

+ [【開発者必見】OS X YosemiteはiPhone/iPadの画面キャプチャ動画を撮ることができる！](http://wayohoo.com/mac/beginners/os-x-yosemite-is-possible-to-take-a-screen-capture-video-of-iphone-and-ipad.html)


というかそもそも、あれを iTunes Connect にアップロードするには OS が Yosemite でないとダメらしいです。なんでやねん。


さらに [iMovie](https://itunes.apple.com/jp/app/imovie/id408981434) 10.0.6 がリリースされてまして、これに App Previews 用動画書き出し機能が搭載されましたよ、と。


> **バージョン 10.0.6 の新機能**
> 
> • OS X Yosemiteに合わせて外観をアップデート  
> • 新しいファイル書き出しオプション：カスタム、H.264、ProRes、オーディオのみ  
> • 任意のビデオフレームをイメージとして共有  
> • iCloudにサインインしているときにMail Dropを使ってHDビデオをメールで送信  
> • クリップの下部をドラッグして、タイムライン内でクリップの一部を選択  
> • 調整バーが常に開いているため、オーディオツールとビデオツールへのアクセスが容易  
> • 古いMacコンピュータでのパフォーマンスが向上  
> • 一部の調整のコピー＆ペーストで起こっていた信頼性の問題に対処  
> • インドネシア語、マレー語、ベトナム語に対応  
> 
> iOSデベロッパ：App Store用のアプリケーションプレビューを作成できます  
> • QuickTime Playerで取り込んだiPhoneおよびiPadの画面収録ビデオをサポート  
> • 動作中のアプリケーションの紹介用にデザインされた11種類のアニメーションタイトル  
> • App Store用に簡単に書き出すことができる共有オプション 

以前のバージョンだと 4:3, 16:9 といったアスペクト比でしかムービーが作成できなかった（たぶん）んですが、今回の 10.0.6 で 750x1334 のムービーが作成できるようになりました。

ただし「新規アプリケーションプレビュー」からプロジェクトを作らないとこの書き出し機能は使えない模様。

![imovie menu]({{site.url}}/assets/entry/2014-10-18-imovie-menu.png)


#### できあがり

<iframe width="420" height="315" src="//www.youtube.com/embed/Z_myYbtF7xo" frameborder="0" allowfullscreen></iframe>

最初に BGM をつけると自分が中学2年生に戻ったような気持ちになってノリノリで編集できます。

[冒頭のリンク](https://developer.apple.com/app-store/app-previews/) にも書かれていますが、15秒〜30秒という制約があってこれがなかなかシビアでした。

AppStore に掲載するためには binary update が必要なようでいまのところ YouTube にのみ載っかっています。
