---
layout: post
title: 当サイトの技術構成
description: サイトをリニューアルしました。
categories: Web It
date:       2021-1-21 12:00:00
author:     "Naoko Kubo"
author-icon: "/assets/images/default.jpg"
author-desc: "合同会社 Interrupt CEO"
header-img: /assets/images/construction.jpg
author-image: /assets/images/construction.jpg
image: /assets/images/construction.jpg
---

<h4 class="blogtitle">Wordpressをやめました</h4>
<p>初期のWebは、HTMLをエディタで直接書いていました。その後、Wordpressが登場して、管理画面から入力すればHTMLがわからない担当者でも、ページの更新が簡単にできるようになりました。</p>
<p>現在も多く使われているのはLAMPで、（Linux,Apache,MySQL,PHP/Perl/Python）サーバーサイドのプログラムで処理をして画面を表示します。Wordpressもその中に含まれます。</p>
<p>我が社ののサーバーが何度目かに落ちて、しかも表示に時間がかかるーとSNSでぼやいてたらセミナーでよくご一緒させていただく<a href="https://www.ey-office.com/blog_archive/2020/11/04/ey-office-site-will-try-to-get-into-jamstack-4/?fbclid=IwAR2OEJ3v2pO_jn8Z2cRQPT_UIy1URBeaA0P2tVXpdhrA-fsJlnqM3fg3CAA" target=_blank >EY-Officeの吉田さん</a>から、Jamstackにしたらとアドバイスをいただきました。</p>
<h4 class="blogtitle">JamStackとは</h4>
<p>Qiitaに記事がありました<a href="https://qiita.com/ozaki25/items/4075d03278d1fb51cc37" target=_blank >Jamstackって何なの？何がいいの？</a></p>
<p>最近よく聞くサーバーレスの仕組みです。AWSにEC2立てたり、さくらサーバー借りたり、お名前サーバー借りたりする必要がありません。</p>
<p>それに代わる、CDNへの配布するサービスとの契約は必要となりますので、サーバーレスと言ってもサーバーサイドに何もないということではありません。</p>
<p>また、データが刻々とかわるのを表示するようなシステムや、大勢で編集するような、SNSのようなシステムにはあまり向いてないと思います。あくまで、一日数回の変更があればいいような、コーポレイトサイトのようなものには向いている仕組みだと思います</p>
<h4 class="blogtitle">このサイトで使っているもの</h4>
- <a href="http://jekyllrb-ja.github.io" target=_blank>Jekyll</a> JamStackのテーマサイトで数がそろっているのと、使いたいテーマがあったので選びました。
- <a href="https://github.com/NaokoKubo/InterruptWeb" target=_blank>Github</a>　公開リポジトリですけど、テーマは頂き物なので作者のライセンスを確認してください
- Amazon Amplify

<p>現在は、エディタで直接直していますが、microCMSも導入してみようと思います </p>

