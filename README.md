# -
■ サービス概要
グッズ特化の推し活用スケジュール管理アプリ。グッズ購入時に、支払い額や申し込み期間、注文状況を可視化するためのアプリ。

■ このサービスへの思い・作りたい理由
フィギュアやVtuberグッズの長い申込みや支払いスケジュール管理が難しいという課題から着想。カレンダー管理では追いきれない注文状況を明確にし、解決したい。

経験として、
Vtuberやフィギュアの注文は到着までに数ヶ月以上かかることもあり、支払いを終えたかどうかや注文したかなどがわかりずらくなってしまう傾向にある。実際に支払ったつもりでできてなかったこともある。また期間があくこともあり予想を上回る出費になりがちなので可視化もしやすいといいなという思いもある。

■ ユーザー層について
スケジュールやメール管理が苦手な人々。特に、フィギュアやVtuberグッズを多く購入するファン層。

■ サービスの利用イメージ
グッズ特化なのでキャラごとに管理する必要がない。
メール保存の手間が省ける。
スマホやPCの容量を取らずに、Webアプリとして軽快に動作。

■ ユーザーの獲得について
グッズ購入を頻繁に行うファン層を対象に、SNSやコミュニティを通じて認知を広げる。

■ サービスの差別化ポイント・推しポイント
「推しスケ」や「TimeTree」とは異なり、グッズ購入特化。具体的な日付の入力が不要で、グッズ購入履歴の管理に特化したインターフェースでより見やすくする。
具体的には一覧で状態(注文待ち・支払い待ち・到着待ち)を明確にすることでカレンダーに依存しない管理を行う。
またホーム画面の一覧表示の上部ではその年の到着待ちの合計金額を表示することで、費用を目に見える状態にしその後のグッズ購入の意思決定の参考にしやすくする。
グッズ一覧はソーシャルゲームアプリのクエスト一覧を参考に作成することで直感的なみやすさを重視する。


■ MVPリリースに必要な機能
グッズ登録・管理機能:

グッズ名、購入金額、申し込み期間、支払いステータスの登録。
簡単なCRUD機能で、登録・編集・削除ができる。
ステータス管理:

支払い済み、未払い、配送待ちなどの状態を管理。
未払通知機能:

Action Mailerを使って未払いのグッズに対する通知機能。
ログイン機能:

Sorceryを使った簡単なメールアドレスとパスワードによる認証。

■ 本リリースに必要な機能
通知機能の強化:

申し込み締め切り、支払い締め切りのリマインダーを追加。
カスタムフィルタ機能:

支払いステータスや期間でグッズをフィルタリングする機能。
複数ユーザー対応:

ログイン機能を強化し、複数ユーザーが同時に利用できる機能を追加。
ソーシャルログイン:

より直感的で使いやすいインターフェースへの改善。


### 画面遷移図
Figma：https://www.figma.com/board/KAd0Yjtj00VSDmlCk6ZSTT/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?node-id=0-1&t=UTJr5pilMu1HxLZL-1

### READMEに記載した機能
- [ ] ユーザー登録機能
- [ ] ログイン機能
- [ ] アカウント情報変更機能
- [ ] 新規追加機能
- [ ] 登録情報編集機能
- [ ] 登録情報削除機能
- [ ] メール通知機能
- [ ] ステータス管理機能

### 未ログインでも閲覧または利用できるページ
- [ ] なし

### メールアドレス・パスワード変更確認項目
- [ ]メールアドレス変更:
- [ ]パスワード変更:
ユーザーがマイページで「アカウント設定」を選択。
現在のパスワードを入力して認証。
アカウント設定画面の修正
フォーム内容
現在のメールアドレス: ユーザーが現在のメールアドレスを確認できるフィールド（非編集可）。
新しいメールアドレス: ユーザーが新しいメールアドレスを入力するフィールド。
現在のパスワード: 確認のために現在のパスワードを入力するフィールド。
新しいパスワード: ユーザーが新しいパスワードを入力するフィールド（任意）。
確認用のパスワード: 新しいパスワードの確認用フィールド。


### 各画面の作り込み
- [ ] 作り込みはある程度完了している（Figmaを見て画面の作成ができる状態にある）