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

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/%E8%A8%BA%E6%96%AD%E7%B5%90%E6%9E%9C%E3%83%92%E3%82%AB%E3%83%AB.png)

タイプ2：助ける人　→ はじめしゃちょー

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/%E8%A8%BA%E6%96%AD%E7%B5%90%E6%9E%9C%E3%81%AF%E3%81%97%E3%82%99%E3%82%81%E3%81%97%E3%82%83%E3%81%A1%E3%82%87%E3%83%BC.png)

タイプ3：達成する人　→ Hikakin

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/%E8%A8%BA%E6%96%AD%E7%B5%90%E6%9E%9CHIKAKIN.png)

タイプ4：個性を求める人　→ Roland

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/%E8%A8%BA%E6%96%AD%E7%B5%90%E6%9E%9CROLAND.png)

タイプ5：調べる人　→ メンタリストDaigo

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/Youtuber%E8%87%AA%E5%B7%B1%E5%88%86%E6%9E%90%EF%BC%93.png)

タイプ6：信頼を求める人　→ マコなり社長

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/%E8%A8%BA%E6%96%AD%E7%B5%90%E6%9E%9C%E3%83%9E%E3%82%B3%E3%81%AA%E3%82%8A%E7%A4%BE%E9%95%B7.png)

タイプ7：熱中する人　→ DJ社長

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/%E8%A8%BA%E6%96%AD%E7%B5%90%E6%9E%9CDJ%E7%A4%BE%E9%95%B7.png)

タイプ8：挑戦する人　→ ラファエル

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/%E8%A8%BA%E6%96%AD%E7%B5%90%E6%9E%9C%E3%83%A9%E3%83%95%E3%82%A1%E3%82%A8%E3%83%AB.png)

タイプ9：平和を好む人　→ 水溜りボンド

![画像名](https://github.com/hiwa1223/Youtuber-self-analytics/blob/master/%E8%A8%BA%E6%96%AD%E7%B5%90%E6%9E%9C%E6%B0%B4%E6%BA%9C%E3%82%8A%E3%83%9B%E3%82%99%E3%83%B3%E3%83%88%E3%82%99.png)

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

プログラムを作成するにあたり、自己満足ではなく実際に使用される物を制作したいと思いました。

そこで診断ツールであれば、SNS等でよく拡散されているので、多くの人に利用されるサービスになると考え制作しました。

また、Youtubeというトレンドの題材を扱うことで興味関心を持ってもらえるように工夫しました。
