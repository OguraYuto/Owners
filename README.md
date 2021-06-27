![petto_logo](https://user-images.githubusercontent.com/71317975/104681968-efebf180-5736-11eb-8869-60dc2e086db1.png)

## サイト概要

ペットを飼っている人が対象で、飼い主とペットの情報を登録して利用する SNS サイトです。  
ペットとの日常を切り取って、日記を投稿したり、友だちを作って会話をすることができます。

URL : <https://petto.work/>

### サイトテーマ

ペットが主役の SNS

### テーマを選んだ理由

私自身これまでの人生の半分以上を愛犬と過ごし、とても身近な存在だったため、動物をテーマにしたいと考えました。  
いつも一番近くで生活している飼い主だからこそわかるペットの可愛さ、魅力を最大限に活かして共有できるようなサービスがあればという想いから「」を作成しました。  
  
同じく動物と生活をする動物好きの人たちと交流をすることで、いろいろな情報や癒しを得ることができ、ペットとの生活がより楽しくなるのではないかと思います。  
  
「私のペットの可愛さをみんなに知って欲しい...」「いろんなペットたちの生活を覗き見してみたい...」
「同じ犬種を飼っている人だからこそわかるあるあるを共有したい...」そんなニーズに応えるコミュニケーションツールとして活用していただければ幸いです。

### ターゲットユーザ

動物を飼っている全ての人たち

### 主な利用シーン

- ペットとのふとした瞬間、出来事を共有したい時  

  → 「日記を書く」から文章を投稿  
- ペットとの特別な 1 日を記録したい時、振り返りたい時  

  → 「思い出を書く」からブログ形式で文章と複数の写真を投稿  

  → カレンダーから見たい日付の思い出を振り返る  
- いろんな動物たちの生活を見てみたい時、癒されたい時  

  → 　検索して投稿や写真を見る  
- 同じ動物仲間と交流したい時  

  → 投稿にコメントを送る  

  → フォローして友だちになり、チャットで会話する  

## 設計書

### ER図
<https://drive.google.com/file/d/15UqbhK-aapvd2XWvi0vgNqAuq3ApDnoe/view?usp=sharing>

## 機能一覧

- ログイン機能
- 投稿機能（日記・思い出、画像投稿が可能です)
- いいね、コメント機能
- フォロー機能
- チャット機能
- 通知機能（相手からいいね、コメント、フォロー、チャットが来るとお知らせに表示されます）
- 検索機能(条件を追加してペットの絞り込み検索が可能です)
- カレンダー(投稿日に印がつきます)
- お問い合わせ(Action Mailer)
- POST & DELETE 非同期通信
- 画像プレビュー
- lightbox2、bxslider(jQueryプラグイン)
- VisionAPI画像認識機能（不適切なコンテンツを検出します）
- レスポンシブ対応(スマートフォン対応)

詳細は下記よりご確認ください

https://docs.google.com/spreadsheets/d/1zYaHEBrVYdKGm5i3wVgvqxcngStebhYQ_qWhvrrkm14/edit#gid=0

## 開発環境

### フロントエンド
- Bootstrap 4.3.1
- SCSS
- JavaScript、jQuery、Ajax

### バックエンド
- Ruby 2.6.3
- Rails 5.2.4

### テスト
- rspec-rails 3.5.2
- factory_bot_rails
 
## 本番環境
- AWS(EC2、RDS、Route53)
- Nginx
- puma
- MySQL 5.7.22


## 使用素材

「silhouette-AC」サイト内画像利用  
<https://www.silhouette-ac.com/#a_aid=5dd6cc067098b&a_bid=d4c0850c>  
「O-DAN」アップロード画像利用  
<https://o-dan.net/ja/>  
「Adobe Fonts」フォント利用(源ノ角ゴシック JP )  
<https://fonts.adobe.com/>
