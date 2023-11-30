# やる気の森(やるもり) 

## 画面遷移図
https://www.figma.com/file/APtDnf6tTURLfPYZeyrXrS/%E3%82%84%E3%82%8B%E3%82%82%E3%82%8A%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?type=design&node-id=0%3A1&mode=design&t=zRG6aChBaXVxw17S-1

## ER図
[![Image from Gyazo](https://i.gyazo.com/de9e8b3e7f44c631a2f025e8f2b00fee.png)](https://gyazo.com/de9e8b3e7f44c631a2f025e8f2b00fee)

## サービス概要
- `やる気の森(やるもり)`は同じような学習目的や目標を持ったプログラミング学習者同士をつなげ、
学習時間を計測し、目標学習時間をチームで達成させる学習時間記録サービスです。
学習時間に応じた「森林」を増やして、絶滅危惧種を救うという世界観で学習に取り組んでいただけます。

## 想定されるユーザー層
- プログラミング学習を継続して行いたい方。
- 学習時間を確保したい、目標時間を設けて達成させたい方。
- 1人だとつい怠けてしまう方。
- プログラミング学習を通して交流を深めたい方。
- 動物に親しみながら勉強を頑張りたい方。

## サービスコンセプト
- 独学での挫折率9割といわれている、プログラミング学習。
ひとりで学習を進めていると「やる気」や「モチベーション」などの理由から学習時間が思うように取れなかったり、
人間どうしても怠けてしまうことがあります。
わたし自身も学習を進める中で、サボろうとしたり、ダラダラしてしまったりすることが何度かありました。
もくもく会に参加したり、学習時間を記録して目標達成できるように学習に取り組むことでなんとか学習を進めていきました。
一緒に学習する仲間を作ることで学習のモチベーションが維持しやすく、気軽に疑問点や相談しやすくなります。
そういった一緒に頑張る仲間を募り、学習時間をみんなで達成できるような、学習管理サービスを考案しました。
- プログラミング学習者に楽しんでもらえるように、記録した学習時間を`Github`の「草」に見立てた「森林」を増やしてもらい、
チーム全員が目標達成すれば「森林」が増えたことで絶滅に瀕している動物たちを救うことができ、
目標未達の場合は絶滅させてしまう危機感から目標達成を促進させます。


## サービスの機能
- 一緒に頑張る仲間を募集したい方は、参加人数・頑張る期間・期間中に達成したい目標学習時間・どんな仲間を探しているかを登録して、参加者を募ります。
- 参加者は募集一覧から参加したいチームを探して、参加できます。
- 参加者は目標時間やタグからチームを検索できます。
- 参加した学習チームの期間になったら、チームの学習記録ページから`学習開始`・`学習終了`・`休憩`ボタンを押して、
学習時間の計測を行います。
- 計測した学習時間をチームの目標学習時間に反映させ、目標までの進捗確認ができます。
- 学習目標を全員で達成できたら、絶滅危惧種を救うことができ、目標未達の場合は絶滅します。
- チーム内でメッセージが送れるようにチャットを送り合うことができます。
- マイページから個人の総学習時間数と絶滅の危機から救うことができた動物も確認できます。
- 学習終了後に学習記録を残せる機能をつけ、XやMattermostへ共有できます。
- 学習を促進させるメッセージや学習記録のつけ忘れ、終了ボタン押し忘れをLINE通知機能でお知らせをします。
- チーム参加回数のランキング機能をつけます。

### 他のサービスと比較して差別化できるポイント
類似サービスとして、以下のものが挙げられます。
- [Studing Tracker]()
  - こちらは学習時間を測り、学習時間を記録することができるサービス。
個人の記録管理のみになっているため、チームで全員で目標達成するという点で差別化。
- [みんちゃれ]()
  - こちらはカテゴリー別で5人1組のチームを作って、習慣化アプリ。
実際の取り組みを写真や文字を投稿して記録していくタイプ。
やる気の森（やるもり）では学習時間を開始、終了、休憩を押し、学習時間を測って学習時間の記録ができる点で差別化。 

- [Study Plus]()
  - こちらは学習時間や内容を個人て記録ができるアプリ。
やる気の森（やるもり）ではチームを作って、チームで目標を達成させることでの交流も目的にしている点や学習時間を測って学習記録ができる点で差別化。

### やる気の森(やるもり)の推しポイント
- よりプログラミング学習者向けに作るためにGithubでの会員登録やGithubで馴染みのある「草を生やす」ように、「森林を増やす」ことで学習時間の記録を残せます。
森林が増えることで絶滅危惧種を救うというゲーミフィケーション要素を追加することで学習の継続を図ります。
動物に親しむこともでき、みんなで楽しく学習に取り組めるのが最大の推しポイントです。

## 実装を予定している機能
  - 認証ログイン機能(Github)
  - プロフィール機能(編集)
  - 個人学習時間一覧
  - チーム目標達成一覧
  - チームメイト募集一覧
  - チームメイト募集登録(アイキャッチ画像)
  - チームメイト募集編集
  - チームメイト募集削除
  - チームメイト募集詳細
  - タグ投稿機能
  - タグ編集機能
  - タグ削除機能
  - 検索機能(時間数・タグ・人数)
  - チーム参加
  - 学習時間計測機能
  - チャット機能(ActionCable)
  - 学習記録機能(WebHook)
  - X共有機能
  - ユーザー勉強中、休憩中、おやすみステータス表示(ActionCable)
  - LINE通知機能
  - 目標達成回数ランキング表示機能
  - テスト機能(RSpec)

### MVP
  - 認証ログイン機能(Github)
  - プロフィール機能(編集)
  - 個人学習時間一覧
  - チーム目標達成一覧
  - チームメイト募集一覧
  - チームメイト募集登録(アイキャッチ画像)
  - チームメイト募集編集
  - チームメイト募集削除
  - チームメイト募集詳細
  - タグ投稿機能
  - タグ編集機能
  - タグ削除機能
  - マルチ検索機能(時間数・タグ・人数)
  - チーム参加
  - 学習時間計測機能
  - チャット機能(ActionCable)
  - 学習記録機能(WebHook)
  - X共有機能

### その後の機能
  - ユーザー勉強中、休憩中、おやすみステータス表示(ActionCable)
  - LINE通知機能
  - 目標達成回数ランキング表示機能
  - テスト機能(RSpec)
