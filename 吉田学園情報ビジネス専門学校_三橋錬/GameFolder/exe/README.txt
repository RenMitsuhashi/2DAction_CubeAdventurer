=============================================================

吉田学園情報ビジネス専門学校 ゲームスペシャリスト学科 三橋 錬
2Dアクションゲーム「Cube Adventurer」(Visual Studio 2015, DirectX9, C++により作成)

=============================================================

このゲームは、「ステージ作成」に重点を置いた2Dアクションゲームです。

=============================================================
動作環境

PC(Windows)


担当箇所

1人(main.cpp, sound.cppは配布物)


制作期間

2021年12月中旬 〜 2022年4月上旬


=============================================================
アピールポイント

・stageload.cppによるcsv形式でのステージデータのセーブ、ロード
csvファイルはdata/stage内にあります。
ステージ作成シーンで読み込まれるファイルは[stage.csv]です。

・当たり判定の最適化
プレイヤーがブロックをすり抜ける、壁に引っかかるなどのバグを解消し、
スムーズな移動ができるようになっています。


=============================================================
タイトル画面の説明

game  : ゲームシーンへ移行(LSHIFTキーと同時押しで3つ目のステージへ)
build : ステージ作成シーンへ移行
quit  : ゲームを終了


=============================================================
ゲームシーンの説明

ステージは全部で3つあり、3つ目のステージは自分で作成することができます。
ステージ作成のシーンへは、タイトル画面で「build」を押すと移行できます。


=============================================================
ゲーム中の操作説明

左に移動 : Aキー
右に移動 : Dキー
ジャンプ : SPACEキー
重力を弱くする : Wキー
重力を強くする : Sキー
ポーズ   : ESCキー


=============================================================
ステージ作成シーン用の操作説明

オブジェクトの配置 : 左クリック
オブジェクトの消去 : 右クリック
画面のスクロール   : 矢印キー左右
配置するオブジェクトの種類を変更 : 矢印キー上下
ゲームのテストプレイ : ENTERキー
ポーズ   : ESCキー(テストプレイ中は開きません。)

(ポーズ画面で「SAVE & CLOSE」を押すとステージデータがセーブされます。)


=============================================================
配置するオブジェクトがブロックだった時の操作説明

ブロックの移動目標地点を動かす : WASDキー(1方向にしか移動しません)
1fごとの移動距離をプラス           : Rキー
目標地点についてからの硬直をプラス : Fキー
カラー値(赤)をプラス : Zキー
カラー値(緑)をプラス : Xキー
カラー値(青)をプラス : Cキー
透明度をプラス       : Vキー

(説明文に「〇〇をプラス」と書いてあるもの限定)
プラス値を*10 : LSHIFTキー
プラス値を*-1 : LCTRLキー


=============================================================
お問い合わせ

メールアドレス
201019@st.yoshida-g.ac.jp