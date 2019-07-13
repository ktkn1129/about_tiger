# Who am I ?
## 4年制大学の情報系学部に通う大学生
- 兵庫県の田舎在住の22歳
- 2020年卒
- 東京か海外に就職したい
    - 将来ヨーロッパに住んでみたいけど、ご飯が美味しいところがいい
- 専攻 : メディアアート
    - 個人のゼミ活動は写真で作品制作
    - ゼミ全体はプロジェクションマッピングのBGMなどを作成
- 写真が好きです
- [ブログ](https://makikomitiger.com/)と[instagram](https://www.instagram.com/kana_nun_)を更新しています
- コミュニティで登壇しています。
    過去のスライドは[こちら](https://speakerdeck.com/ktkn1129)から
- Alexa Skillを作成しました
    - [today's coordinator](https://www.amazon.com/Kana-K-todays-coordinator/dp/B07F1NWRF3/ref=sr_1_1?keywords=Kana.K+alexa+skill&qid=1562982991&s=gateway&sr=8-1)

## あだ名は[たいがー](https://twitter.com/MakikomiTiger)
### 気軽にたいがーと呼んでください。
- 由来は`Makikomi is trigger.`
    - [JAWSDAYS 2018](https://jawsdays2018.jaws-ug.jp/)でLTをした際に海外ゲストが来るということで、英語でスライドを作成した
    - 自身が巻き込まれた経験から、"巻き込みはきっかけになる"と書きたかったのだが、`trigger`を`tigger`と誤字をしてしまったところ、後日指摘され、そこから、**MakikomiTiger**、**たいがー**と呼ばれるようになる

# What will I want to do?
国籍関係なく、人々を驚かせるソフトウェアサービスを提供したい
- 情報をわかりやすく可視化できるツール
    - 機械学習を使って傾向を表せたら面白そう！

- 今はエンジニアとして何かを作って喜ばれることにも興味がある
    - 新しい技術を探すこと、聞くことが好き
- 色々な方面に興味が出てきたので、様々な人と人を繋げ、話すことができるCSもいいのではないかと思い始めた
    - 色々な要望を聞くことで相手の求めるものがわかるようになるので、マーケもしてみたくなってきた

# What am I interested in?
## 将来サービスを作成するために、色々なサービスを触ってみたい
- 機械学習
- キャッシュレス
- コミュニケーションツール
- 可視化ツール

# What did I do?
ユーザーグループでのコミュニティ活動やインターンシップを行っていました
使用言語 :  主にPython、少しJavaScript
使用ツール : [box](https://www.box.com/ja-jp/home) API、[bitly](https://bitly.com/) API、 [boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html?id=docs_gateway)、 Github、[Trello](https://trello.com/ja)

##  ユーザーグループでのコミュニティ活動
- 大学2年生の時、Amazon AlexaのLTを聞いたことがきっかけでユーザーグループに参加し始める
- Amazon Alexaに関するLTをJAWSUG 神戸支部で何度か行う
- [JAWS DAYS 2018](https://jawsdays2018.jaws-ug.jp/)でそれまでのコミュニティ活動に関するLTをし、[3位](https://speakerdeck.com/ktkn1129/why-do-i-stand-here-now)を獲得
    - そのことがきっかけで海外のエヴァンジェリストと話し、いまだに交流がある
- その後、高知で行われた[四国クラウドお遍路](http://ohenro.jaws-ug.jp/)でセッション、[コミュニティリーダーズサミット in 高知](https://eventregist.com/e/CLS_Kochi?lang=ja_JP)でLTを行う
- Amazon Alexaのハンズオンを大学で実施
- Amazon Alexaのユーザーグループ、AAJUGの運営を手伝う
    - AlexaDay2019では企業に対し、スピーカー交渉を行った
- コミュニティ活動を通じて、タイ・韓国・シンガポール・アメリカ・イギリス・スペインの人々と交流を行った
    - AWS re:Invent 2018に参加したとき、とにかく色々な人に話しかけ、SNSなどでやり取りをしている
- コミュニティ活動をきっかけにインターンシップをしている
- [JAWS DAYS 2019](https://jawsdays2019.jaws-ug.jp/)では、機械学習に関するLTを行い、[2位](https://speakerdeck.com/ktkn1129/katukowotukekirenaisi-falseji-jie-xue-xi-my-machine-learning-that-i-cant-show-off)を獲得した

### 学生コミュニティ(JAWS-SG)も準備中

## インターンシップ
AWSに関してもっと深く学びたい、触ってみたいと思い、インターンシップ先を探したが、うまく見つからなかった。
そこで、ユーザーグループに参加している方が所属している企業なら可能ではないかと思い、インターン制度がなかった、[株式会社サーバーワークス](https://www.serverworks.co.jp/)にインターンをさせて欲しいとお願いし、今も引き続いてさせていただいている。

### インターンシップで何をしているか
#### 製品のハンズオン準備における効率化のためのスクリプト作成
`GitHubの非公開リポジトリにて作業`
1.  コマンド引数によるインスタンスの起動、停止の切り替え
- boto3
- STS対応
- 複数アカウントに跨ったEC2インスタンスの起動、停止
- 起動、停止したアカウント、インスタンスIDの出力

2. 各ハンズオン用アカウントのクレデンシャル情報を記入したテキストファイルの作成、ファイル格納
- boto3
- 各アカウントのキーペアが既に存在する場合、もう一度発行しなおすように設定
- テキストファイルに、自社サービスに関するものも含むクレデンシャル情報を記入させる
- それらをアカウント番号ごとにフォルダを分けて作成し、そのフォルダを一つのフォルダにまとめる

3. box APIを使って、パスワード、期間を設定したフォルダに、先ほど作成したフォルダを格納し、そのURLを短縮させる
- 先ほど作成したフォルダをboxの指定のフォルダ内に格納する
- 期限、パスワードを設定した上で、そのフォルダの共有用URLを[bitly](https://bitly.com/)のAPIを使用し、短縮させ、出力させる

#### Slack botの作成
- AWS Lambda / Incoming Webhooks
- 各週、決まった時間にランダムなコメントがポストされるように設定

# Advantage Point
- 積極性がある
- 勝負所を見定められる
- コミュニケーション能力が高い

# Disadvantage Point
- 慎重ではない
- 語調が強くなりやすい
- 顔に考えていることが出やすい
