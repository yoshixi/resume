# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|増渕 佳輝|
|Blog|[ブログ](https://yoshixj.com)|
|Quiita|[Quita](https://qiita.com/yoshixj)|
|Twitter|[@yoshixj](https://twitter.com/yoshixj)|

## スキル
### 言語
- Ruby
- Go
- GAS
- マークアップ
- js

### フレームワーク、プラットフォーム
- Ruby on Rails
- Golang
  - WF [99designs/gqlgen](https://github.com/99designs/gqlgen) / [go-chi/chi](https://github.com/go-chi/chi)
  - ORM [volatiletech/sqlboiler](https://github.com/volatiletech/sqlboiler)
- Puppeteer
- Docker
- Vue
- Haroku
- GCP
  - GAE/GCS/CloudSQL/CloudTasks/CloudScheduler/CloudFunction
- Firebase

### その他
- github
- slack/chatwork
- Asana
- Redash

## 言語
- 日本語
  - ネイティブ
- 英語
  - 英語ドキュメントをなんとなく読める程度
  - TOEIC: 550点 (2015年の大学入学時に受けたもの)

## 強み
- 経験上新規開発などが多く、アーキテクチャを考えつつ、コーディングした経験がおおいです。
- コードを書く以外も食わずぎらいをせずにやってきました。

## やったことはないが興味があるもの
- 小さい規模の開発が多かったので、大規模の開発に入ってみたいです。

## 職務経歴

中央大学情報工学科卒業。
在学中から

- HP制作会社
- 大手プログラミング教育会社
- 開発メンバーが一桁のチーム

にて業務をしてきました。


### 2019/08 -  現在 : 株式会社NiCOLA
- D2C事業の支援ツールの開発
- 使用技術: Golang/Nuxt x Typescript/GAE/CloudTasks/ShopifyAPI/Firestore

自社のD2C事業を支援するツールの開発を行っています。
責務が分散した、軽いAPIなどを作ることが多くなるため、Golangをサバーサイド言語としてさいようしてます。
WFとしてはgoaを採用しています。Open APIでスキーマ駆動で開発できる恩恵と、サービスが分散することを予測しておりOpenAPIの記述を矯正することで、将来のメンテコストを下げる要因になるのではないかと考えています。

### 2020/02 -  : 株式会社Doorkel
- 教育機関向けマーケティング支援ツールの開発
- 仕様技術 Rails/Vue/ZoomAPI

バックエンドにRails、フロントエンドにNuxtを仕様して開発をおこなっています。


#### 2018/08-2019/08: 株式会社NiCOLA
- テイクアウトアプリ [mecimo](https://mecimo.jp/)の開発
- 使用技術: Rails5/GAE/GCS/CloudSQL/Docker/Swagger/Stripe/Vue

RailsをつかったAPIの開発をしました。
認証にJWTを使用しました。
このプロジェクトとは新規で設計からぜんぶやらせてもらいました。
APIのシリアライザーとして、fast_jsonapiも使いました。 [fast_json:APIについては、Quiitaに投稿しました](https://qiita.com/yoshixj/items/6499490f6fbefea05cae)
またGAEのflexible環境を使い、RailsをGCP上にホスティングしてました。
決済にStripeを使用したので、そのトランザクションを慎重に実装しました。

また少しですが、業務委託の方にも手伝ってもらい、管理画面の実装も行いました。
管理画面の実装としては、仕様変更、SEOなどが必要ない点などを考慮し、Vue.jsでSPAで実装しました。
データの管理として、Vuexを使用しました。

#### 2018/08-2019/01: 株式会社NiCOLA
- お気に入りのお見せをストックできる、[グルポケ](https://lp.gpocket.jp/)というアプリを開発してました。
- 使用技術: heroku/Rails4/postgres/PostGis/Docker/Redash/Swagger

Railsを使ったAPIの開発をしてました。
位置情報を扱うために、PostGisをつかっていました。
インデックスを張り替えるなどして、パフォーマンスをあげたりもしました。
また、開発環境をdocker-composeに載せ替えもしました。
途中で社内のエンジニアが自分ひとりになったこともあり、開発マネージャーのようなポジションになりました。業務委託でリモート勤務のiOS開発者の方とのコミュニケーション改善も行っていきました。

失敗談としては
- 既存のpostgis用のadapter gemをうまく使いこなすことができず、modelに直接クエリを書いてしまったこと
- 初期に設計していたDBの設計よくなかった。(リレーション関係がまず、statusの管理など)

### 2017/07 - 2018/08: 株式会社div
職務: インターン、メンター

- RubyOnRailsを教えるプログラミング講師のメンターをしていました。
- 月間で一番受講生から評価をもらったメンターにもなりました。
- 拠点責任者になり、教室の運営業務などもおこないました。
- 環境: slack/github/jobcan

株式会社divはメンターとして、コミュニケーションの基礎を学ぶことができた環境でした。
お金を払って教室にきてくれている受講生に、気持ちよくプログラミングを学んでもらうためにはどうするのがいいか考えて接客しました。
一番の得られたものは傾聴力です。様々な人と働く上で、相手がどう思っているかを常に聞く姿勢はとても大切なものだと日々感じています。
また、成長しているベンチャー企業の会社の文化も生で感じることができた会社でした。

### 2016/08 - 2017/08: 株式会社フォーデジット

#### ホームページの改修業務
職務: コーダー

- HTML/CSS/JSで作られたホームページのの改修をしてました.
- photoshop, illustrator でくられたデザインをコード反映させるようなお仕事です。
- 開発環境: subversion/mamp/chatwork

1年ほどアルバイトという形で働かせていただきました。
サイトとしては、大手不動産会社のホームページともあり、中規模〜大規模のHPのマークアップ改修業務を行いました。
正直先端な技術とかは使ってはなく、複数箇所にまたがるような同じパターンの変更などもあり、時には数十のHTML/CSSファイルのコードを一括で置換するなどの作業も行いました。


## 課外活動

### 過去の登壇資料
* [Speaker Deck](https://speakerdeck.com/yoshixj)

