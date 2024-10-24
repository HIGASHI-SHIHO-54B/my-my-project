■サービス概要
ユーフォーキャッチャーで獲得したグッズを獲得にかかった金額、店舗別で登録できるサービスです。
一覧で管理することによって獲得へ難易度が高い傾向の店舗を可視化することができます。
また、自分がどれぐらいお金を使ったかを把握することで、使い過ぎないようになります。

■ このサービスへの思い・作りたい理由
私はユーフォーキャッチャーをするのが好きで、時々友人とゲームセンターに行っています。
様々な店舗に足を運んでいますが、お店によって獲得難易度に差があると感じるようになりました。しかし体感でしかなかったのでなんとなくでしか友人に話せず、記録の必要性を感じました。また、難易度が高いと回数を重ねることになり、結果金額が積み上がってしまいます。それを防ぐためにどれぐらいの金額が獲得にかかったかを登録し難易度の可視化ができればもっとユーフォーキャッチャーライフを楽しめるのではと思い開発に至りました。

■ ユーザー層について
学生・社会人を対象としています。ユーフォーキャッチャーに来ている客層がだいたいこのように感じています。ただお金をしっかり使えるのは社会人なのでこの層がメインになっていくのかと思います。

■サービスの利用イメージ
ユーフォーキャッチャーで獲得したグッズを金額、店舗別で登録できます。それにより入手したいグッズがあった場合、入荷対象店舗同士の過去の記録を比較することでより効率的に獲得ができるようになります。また記録を取ることでお金の使い過ぎも防ぎます。

■ ユーザーの獲得について
SNSでの告知

■ サービスの差別化ポイント・推しポイント
このサービスは登録したグッズを金額、店舗別で見ることができます。ユーフォーキャッチャー専用なので獲得できない場合も、金額の登録ができるようになっています。


■ 機能候補
MVPリリース時に作っていたいもの：獲得商品の登録ページ、商品一覧ページの作成、商品削除、編集機能、会員登録、ログイン機能
本リリースまでに作っていたいもの：トップページ、タグ付け、検索機能

■ 機能の実装方針予定
一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもの:
Stimulus Autocomplete（Rails7 ）導入し検索候補の表示を行う予定です。

### 画面遷移図
Figma：▽獲得グッズ一覧・登録・編集・削除・ヘッダーのプルダウン
       https://www.figma.com/design/Dz3OMiWCeZAX7yX13HgNSc/my-my-project?node-id=3-4&node-type=frame&t=VgCR2wp6YlNGBEdA-0

       ▽ログイン・ユーザー登録・プロフィール・プロフィール編集・メールアドレス変更申請・メールアドレス変更画面・パスワードリセット申請・パスワードリセット
       https://www.figma.com/design/Dz3OMiWCeZAX7yX13HgNSc/my-my-project?node-id=4-145&node-type=canvas&t=VgCR2wp6YlNGBEdA-0

       ▽【本リリースまでに作成したいもの】タグ付け・検索欄・トップページ
       https://www.figma.com/design/Dz3OMiWCeZAX7yX13HgNSc/my-my-project?node-id=10-401&node-type=canvas&t=VgCR2wp6YlNGBEdA-0

### READMEに記載した機能
- [ ] ユーザー登録機能
- [ ] ログイン機能
- [ ] パスワード変更機能
- [ ] メールアドレス変更機能
- [ ] 獲得グッズ登録機能（画像投稿含む）
- [ ] 獲得グッズ一覧機能
- [ ] 獲得グッズ編集機能
- [ ] 獲得グッズ削除機能
- [ ]プロフィール閲覧
- [ ]プロフィール編集
- [ ]タグ付け
- [ ]検索欄
- [ ]トップページ

### 未ログインでも閲覧または利用できるページ
- [ ] トップページ
- [ ] ログイン機能
- [ ] パスワード変更機能
- [ ]メールアドレス変更画面

### メールアドレス・パスワード変更確認項目
直接変更できるものではなく、一旦メールなどを介して専用のページで変更する画面遷移になっているか？
- [ ] メールアドレス
- [ ] パスワード

### 各画面の作り込み
画面遷移だけでなく、必要なボタンやフォームが確認できるくらい作り込めているか？
- [ ] 作り込みはある程度完了している（Figmaを見て画面の作成ができる状態にある）