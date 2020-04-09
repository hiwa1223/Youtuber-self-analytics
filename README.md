# README

## 1.アプリ説明

YouTuberを題材にした診断ツールです。

SNS等で拡散されやすい、気軽に触って頂いて楽しめるアプリケーションを開発致しました。

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/YouTuber%E8%87%AA%E5%B7%B1%E5%88%86%E6%9E%901.jpg)

アイディアの元になっているのは、エニアグラムと呼ばれる心理テストです。

就職活動などで利用される診断ツールの一つです。


## 2.使い方

スタートボタンを押すと設問が表示されますので、それに順次回答していきます。

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/Youtube%E8%87%AA%E5%B7%B1%E5%88%86%E6%9E%902.png)

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/Youtuber%E8%87%AA%E5%B7%B1%E5%88%86%E6%9E%904.png)

## 3.診断結果について

当アプリでは、エニアグラムで使用される９タイプをそれぞれ人気YouTuberに当てはめて診断することしました。

タイプ1：改革する人　→ Hikaru



タイプ2：助ける人　→ はじめしゃちょー

タイプ3：達成する人　→ Hikakin

タイプ4：個性を求める人　→ Roland

タイプ5：調べる人　→ メンタリストDaigo

タイプ6：信頼を求める人　→ マコなり社長

タイプ7：熱中する人　→ DJ社長

タイプ8：挑戦する人　→ ラファエル

タイプ9：平和を好む人　→ 水溜りボンド

なお、設問内容はオリジナルです。

ただし、回答内容に対して、タイプが一致するように工夫しました。

## 4.環境

HTML　+ CSS + Jquery(Javascript) で構成しております。

デプロイはHerokuで行っています。

## 5.プログラム内容

Jqueryのプログラムは以下の通りです。

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/youtuber%E8%87%AA%E5%B7%B1%E5%88%86%E6%9E%90(Jquery).png)

書いてある内容を説明をすると、

「btn」というクラスを「クリック」したら実行。HTMLの回答項目について「btn」というクラスを付与しているので

設問に対して回答したら、Jqueryが動きます。

プログラムが動くと、このボタンが属していた「div」要素のdisplayをnoneにして表示を非表示にします。

次にaタグに指定してあるidの要素に飛んで、次の質問に切り替わります。

HTML(一部)は以下の通りです。

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/Youtuber%E8%87%AA%E5%B7%B1%E5%88%86%E6%9E%90(HTML).png)

## 6.制作の背景

プログラムを作成するにあたり、自己満足ではなく実際に使用される物を制作したいと思った。

診断ツールであれば、SNS等でよく拡散されているので、多くの人に利用されるサービスになると考え制作した。

また、Youtubeというトレンドの題材を扱うことで興味関心を持ってもらえるようにした。
