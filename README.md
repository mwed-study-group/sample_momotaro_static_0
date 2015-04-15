# sample_momotaro_static

## これは…
git/githubの演習用です。

## 使い方
### githubへ登録
演習の主催者がzipファイルをダウンロードしてきて、演習に使うリポジトリを登録します。

### 演習者向けのWebサーバを準備
Webサーバのドキュメントルートを、cloneしたリポジトリの`html`に設定する。
`index.html`が見られることを確認しておく。

## 演習
演習は下記、3パターン。
4人ひと組で行う想定です。

1. 新規ファイルの追加
2. ファイルへの変更
3. ファイルへコンフリクトの起きる変更

### 新規ファイルの追加
１人ひとつ案件を持ってもらってください。

#### 案件1-1 桃太郎誕生と成長
* `/html/first.html`を作成。
* htmlには下記テキストを表示すること。
```
老夫婦が川で拾った桃から子供が生まれて、桃太郎と名付けられ大きく育った。
```
* `/second`へのリンクをつけること

#### 案件1-2 鬼退治の決意
* `/html/second.html`を作成。
* htmlには下記テキストを表示すること。
```
桃太郎は旅人から鬼ヶ島に住む鬼に困っているひとの話を聞き、退治を決意した。
```
* `/third`へのリンクをつけること

#### 案件1-3 道中で同志との出会い
* `/html/third.html`を作成。
* htmlには下記テキストを表示すること。
```
桃太郎は鬼退治に出発、道中であった犬、雉、猿をきびだんごと引換に家来にし、ついには鬼ヶ島に到着する。
```
* `/fourth`へのリンクをつけること

#### 案件1-4 鬼達との対決
* `/html/fourth.html`を作成。
* htmlには下記テキストを表示すること。
```
鬼ヶ島で桃太郎は鬼達と対決するが、犬、雉、猿の必死の活躍があり、勝利した。無事困っていた人たちに報告し、生まれた村に帰っていった。
```
* `/end`へのリンクをつけること

### ファイルの変更と作業中の別リリースの反映
すでにあるファイルを変更してもらいます。
前回担当してもらった案件と違うファイルを使う案件を持ってもらってください。
作業を始めて、ローカルリポジトリにコミットをする直前に止めてもらって、
案件2-xを講師がやり、masterにマージします。
その後、masterの内容を各自のブランチに取り込んでもらってから、続きの作業を行ってもらいます。

#### 案件2-1 桃太郎誕生と成長をもう少し詳しく
*物語例*
昔々あるところに老夫婦が住んでいました。
あるとき、おばあさんが川で洗濯をしていたときに大きな桃を拾いました。
おじいさんの帰ってから、桃を切ろうとすると、中から元気な男の子が飛び出しました。
老夫婦は、男の子に「桃太郎」と名付け、大切に育てました。

#### 案件2-2 鬼退治を決意をもう少し詳しく
*物語例*
あるとき、桃太郎は、村に通りがかった旅人から、街道の先にある村で鬼が乱暴狼藉がひどく困っていることを聞きました。
桃太郎は老夫婦の教育の賜物か、正義感強く育ったので、見過ごすことができなくなり、退治に向かうことを決意しました。

#### 案件2-3 道中で同志との出会いをもう少し詳しく
*物語例*
桃太郎は鬼退治に出発、道中であった犬、雉、猿をきびだんごと引換に家来にし、ついには鬼ヶ島に到着する。
桃太郎は、鬼に困っている人を助けにどうしても行きたいと老夫婦に相談しました。
老夫婦は止めましたが、桃太郎の決意は固かったので、最後には折れて、協力をすることにしました。
おじいさんは知り合いのツテを駆使して、業物の太刀の童子切安綱と源為朝が使ったと言われる小桜韋黄返威鎧を桃太郎のために誂えました。
おばあさんは、桃の絵のついた旗印と、お弁当にと、クックパッドで検索して作ったきびだんごを用意しました。
桃太郎は老夫婦に見送られ、意気揚々と街道を進んでいきました。
途中、腹をすかせてフラフラしていた、犬、猿、雉にきびだんごを恵んだところ、ついてきてくれることになり、総勢一人と三匹の軍勢となりました。
鬼に困っている村に着き、村人に様子を尋ねると、鬼は海の上の無人島に居を構えているそうでした。
翌朝、桃太郎軍は、鬼の住む島、通称鬼ヶ島に進軍していきました。

#### 案件2-4 鬼達との対決をもう少し詳しく
*物語例*
鬼ヶ島で桃太郎は鬼達と対決するが、犬、雉、猿の必死の活躍があり、勝利した。無事困っていた人たちに報告し、生まれた村に帰っていった。
鬼ヶ島が見えてくると、桃太郎は櫂を漕いでいる猿に、ぐるりと島を回るように命じました。
上陸しやすいところは鬼が見張りを立てていると踏んだのです。 半周ほど回ったところでしょうか。急峻な崖でとても上陸できそうもないところがみつかりました。
雉を偵察に出し、鬼が見張っていないことを確認したところで、猿に長い縄を持たせて、崖を登らせ、上にある太い木に結ばせました。
桃太郎は縄を掴むことのできない犬を背中に背負い、登ってゆきました。
崖の上は、ちょうど鬼の住む城の真裏。桃太郎は夜まで待ち、夜襲をかけることにしました。
夜になると、犬が酒の臭いがする、と桃太郎に伝えてきました。
村人に頼んでおいた酒が、鬼たちに届き、案の定酒盛りが始まったようです。
鬼たちが酔いつぶれる頃合いをじっと待ちます。
雉の目が効くようになってくる朝方まで辛抱したところで、人一倍大きな鬨の声を上げ、攻めこんで行きました。
突然の襲撃に驚いた鬼たちは二日酔いの頭を抱えながら頭領を置いて逃げていってしまいました。
童子切安綱を引っさげて、城の奥深くにずんずん進んでいくと、ムダに金ぴかな部屋があり、中から大きないびきが聞こえてきました。
ガラッ。スタスタばっさり。
桃太郎の作戦が当たり、見事討ち果たしたのでした。
村に戻り報告すると、皆たいそう喜び、桃太郎にとても感謝したのでした。

感謝の宴を催すと村人が言ったのですが、桃太郎はそそくさと帰り支度をして、老夫婦の待つ村へと帰っていったのでした。

#### 案件2-x (不具合)トップに次へのリンクがない
トップにfirst.htmlへのリンクを追加してください。


### コンフリクトの起きるファイルの変更
コンフリクトの起きる変更をしてもらいます。
案件3-0は講師が担当し、残りは好きな案件を選んでもらってください。
案件3-0から順にmasterにマージしていきます。

#### 案件3-0 村->町
全HTMLファイル中の村を町に変更してください。

#### 案件3-1 桃太郎->バナナ太郎
全HTMLファイル中の桃太郎をバナナ太郎に変更してください。

#### 案件3-2 犬->ハイエナ
全HTMLファイル中の犬をハイエナに変更してください。

#### 案件3-3 猿->チンパンジー
全HTMLファイル中の猿をチンパンジーに変更してください。

#### 案件3-4 雉->ダチョウ
全HTMLファイル中の雉をダチョウに変更してください。
