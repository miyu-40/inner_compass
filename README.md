### ■サービス名：理想の上司

### ■サービスの概要
Chat GPTが理想の上司となって、現在立ち向かってる困難な状況を小さなミッションに分けてくれ、また、セルフコンパッションを実践できるようサポートしてくれるアプリです。
セルフコンパッションとは、自分自身に対して優しく、理解を示し、自分の苦しみや失敗を受け入れることです。このアプリでは自分自身に応援の言葉をかける練習ができるようにサポートしていきます。

### ■画面遷移図
Figma：https://www.figma.com/file/1mTdQdwdl248G26xx2s3h9/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?node-id=0%3A1&t=kJyPWgHe2Gr3P0xi-1

### ■ER図
draw.io：https://drive.google.com/file/d/175NYeVNsr5_KLSS37XR93r0AAbQ37JuZ/view?usp=sharing

### ■メインのターゲットユーザー
- 自分を責めてしまったり否定してしまって、何かを始めることや目標を立てることに臆病・不安・心配になってしまっている人
- 将来のことをマイナスに考えて、今のアクションプランを立てるのが苦手な人
- 今何をすればいいのか不安な人・わからない人
- 1人で目標に向かってアクションを起こす時、過去に挫折してしまった人

### ■ユーザーが抱える問題
- 現状の把握や方向性が不明確であり、選択肢の多さや優先順位の決めづらさから迷いや不安が生じている
- 将来に対して悲観的に考えることで、現状のアクションプランを立てることが苦手になり、先延ばしや行動力の欠如が生じる
- 自分を責めたり否定することで自己肯定感が低くなり、何かを始めることや目標を立てる際に臆病で不安や心配がつきまとう
- 1人で目標に向かってアクションを起こす際、サポートや励ましの言葉が不足しているため、孤独感が強くモチベーションが維持できない

### ■解決方法
- Chat GPTを用いてゴール設定を行い、達成時に称賛を与えることで、他人との比較ではなく、自分だけのゴールや小さな目標の達成を祝うことができる。それにより、自分自身の成長を重視する価値観を構築し、自己評価を向上させる
- Chat GPTを通して現状を把握し、具体的なアクションプランを提案することで、選択肢の多さや優先順位の決めづらさを軽減し、方向性を明確にする
- セルフコンパッションリマインダーを設定し、定期的に自分を励まし、自分への過度な期待や自己批判を緩和することで、自己肯定感を高める
- 行動できない時、他のユーザーと協力することで、定期的に応援コメントを受け取り、孤独感や心の負担が軽減され、行動できるようになったり、継続力を高められる

### ■実装予定の機能
1. ユーザー登録・ログイン機能
  - サインアップ
  - ログイン
  - ログアウト
  - パスワードリセット
2. トップページ：セルフコンパッションを紹介
3. ユーザーの困難な状況に合わせてChat GPTがミッション(アクションプラン)を生成する機能
  - 困難な状況を入力できる
  - Chat GPTによってミッション(アクションプラン)が提案される
  - 必要なミッションを選択・編集・追加できる
4. セルフコンパッション促進機能
  - ミッション選択後、自分を励ます言葉を入力・確認できる
  - LINE通知でセルフコンパッションを行っているかの確認や応援の言葉が送られてくる
  - 通知の時間や頻度を設定できる
  - ミッション中のホーム画面で応援の言葉がランダムで表示される
  - ミッション終了後に自分を褒めるよう促す
  - ミッションを全て終了し、困難を乗り越えた後にChat GPTによって達成した困難に応じてユーザーの強みが発見され、褒め言葉が送られる
5. ミッション依頼(他のユーザーとの協力)機能
  - 落ち込んでいる・1人じゃ先に進めないなどのとき、他のユーザーに助けを求める＝ミッション討伐依頼を行える
  - 討伐依頼一覧ページにて他ユーザーは依頼を確認できる
  - 他のユーザーは応援の言葉をコメントできる
  - 他のユーザーから応援メッセージが届いたときにLINEに通知される
  - ミッションがクリアしたら、協力してくれたユーザーにもLINEに通知される
6. マイページ
  - ユーザー名・アバター・メールアドレスを編集できる
  - ユーザープロフィール設定
    - 年齢、性別、職業などの属性情報を入力できる（属性情報をChat GPTのプロンプトに組み込むことで、精度をあげる）
    - 応援スタイルの選択（友達からの応援、先輩・上司からの応援など）
  - 現在のミッション達成状況（達成数）や困難・ミッション一覧を確認できる
7. 過去の記録の表示
  - 達成した困難・ミッションや発見された強み、応援メッセージを確認できる

### ■なぜ作ろうと思ったのか
私自身が長い間、他人からの目を気にして、他人の評価が全てだと考えていました。そのため、自分自身に目を向けることができず、他人ばかりを見ているうちに、自分が何をしたいのか、何をしたら楽しいのかがわからなくなり、自分の選択にも自信を持てなくなっていました。でもそれは誰かのせいでもなく、過去のせいでもなく、自分が何かをするたびに自分を否定しているからだと気づきました。
私のように自分を責めてしまったり否定してしまって、何かをすることに臆病・不安・心配になってしまっている人や自分のいいところを受け入れられない人、自分のいいところを言われても認められない人が自分を信頼して自分が一番の味方になってあげられるようになってほしいと思ったため、このアプリを作成しようと思いました。

### ■スケジュール
企画〜技術調査：4/30〆切
README〜ER図作成：5/7〆切
メイン機能実装：5/8 - 6/4
β版をRUNTEQ内リリース（MVP）：6/4〆切
本番リリース：6/18〆切