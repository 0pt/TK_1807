# 家族の在宅管理App

[![Product Name](  )](  )

## 製品概要
### Home x Tech

### 背景（製品開発のきっかけ、課題等）
- 背景：
近年，日本では共働きの核家族が多く、親は子供が家に帰ってきたか心配になるケースが多く存在します．
そのような中で，"子供が家に帰って来た"という情報が確認できるシステムがあれば、不安を軽減できます。

- 着目した顧客：
子供のいる親

- 顧客の課題・現状：
家族が家に帰ってきているか知りたいが、
家族のプライバシーも尊重したい。

### 製品説明（具体的な製品の説明）
* 玄関に置いたLINE Beaconで家族の帰宅/外出を検知
* "家に帰って来た人"(家から出かけた人)を通知してくれるLineBotを作成し，簡単に確認ができるシステムを作成しました。

<img width="355" alt="2018-10-28 13 18 50" src="https://user-images.githubusercontent.com/44076009/47611987-1a98f380-dab4-11e8-8702-616da4615b2b.png">

### 特長
スマホとLine Beaconがあれば手軽に実現できます。

#### 1. 特長1
スマホで家族の帰宅/外出記録をタイムスタンプとともに確認できる。

#### 2. 特長2
(未実装)外出先をスピーカ(Clova)から報告できる。発声による簡単な操作

#### 3. 特長3
(未実装)子供は門限までに帰るとポイントがもらえる

### 解決出来ること
* 家族が今どこにいるのか、適度なプライバシーを保ちつつ管理できます。

### 今後の展望
* Clovaとの連携 (外出先をスピーカから報告できる、など)
* 門限を守って帰宅した子供にポイントをあげる
* 年何回外出した、などのライフログを後から閲覧できるようにする

## 開発内容・開発技術
### 活用した技術
#### API・データ
* LINE Messaging API

#### フレームワーク・ライブラリ・モジュール
* flask

#### デバイス
* LINE Beacon
* Clova Friends

### 独自開発技術（Hack Dayで開発したもの）
#### 2日間に開発した独自の機能・技術
企画・開発の全工程
