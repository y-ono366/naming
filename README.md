# 英単語命名表

#### オブジェクト・変数の操作

 単語        | 意味
-------------|--------------------------------
 create      | 構築する
 destroy     | 壊す
 serialize   | シリアライズする
 deserialize | 復元する
 lock        | ロックする
 unlock      | ロックを解除する
 activate    | アクティブにする
 deactivate  | 非活性化する
 clear       | ～の中身だけを消す
 delete      | ～を外側ごと消す
 erase       | ～を消す（復元不可能）
 trash       | ～を消す（復元可能にしておく）
 create      | ～を空の状態から創る
 generate    | ～を変換して生成する
 make        | ～を作る（部品を作る）
 build       | ～を構築する／部品を組み立てる



#### 外部と入出力
 単語    | 意味
---------|---------------------------------
 load    | データや設定をメモリに展開する
 save    | メモリの内容を外部に保存する
 entry   | 入力する（書きっぱなし）
 input   | 入力する（チェックされる）
 enroll  | 入会する
 output  | 出力する（そのまま）
 export  | 外に出力する（加工して）
 import  | 中に取り込む
 print   | 書き出す（標準出力）
 store   | オブジェクトを格納する
 restore | 格納したオブジェクトを復元する
 backup  | データをバックアップする
 restore | データをバックアップから復元する


#### データベース・ファイル
 単語       | 意味
------------|----------------------------
 connect    | 接続する
 disconnect | 切断する
 fetch      | 条件を指定して取り出す
 insert     | DBレコードを挿入する
 update     | DBレコードを更新する
 delete     | DBレコードを削除する
 rollback   | DBレコードの更新を元に戻す
 open       | 開く
 close      | 閉じる
 read       | 読む
 write      | 書く


#### データの取得
 単語    | 意味
---------|----------------------------------
 get     | ～を取得する
 set     | ～を設定する
 unset   | ～を設定しない
 reset   | ～を初期化してやり直す
 to      | ～を変換する（convert_toと同じ）
 parse   | ～を変換する
 exclude | ～を排除する
 ignore  | ～を無視する

#### データの計算
 単語           | 意味
----------------|------------------------------
 compute        | ～を計算する（一般的な計算）
 calculate      | ～を計算する（複雑な計算）
 vectorize      | ～をベクトル化する
 add            | ～を追加する
 remove         | ～を削除する・取り除く
 increment(inc) | ～に１加算する
 decrement(dec) | ～から１減算する
 gain           | ～を増やす
 reduce         | ～を減らす


#### データの格納と取り出し
 単語       | 意味
------------|--------------------------
 push       | スタックに収める
 pop        | スタックから取り出す
 push       | スタック以外に収める
 pull       | スタック以外から引き出す
 stash      | 隠す
 pop        | 引き出す
 enqueue    | キューに入れる
 dequeue    | キューから取り出す
 sample     | 無作為に取り出す
 fetch      | 投稿等を取り出す
 post       | 投稿等を投じる
 search     | 検索する
 retrieve   | 検索して取り出す
 find       | ある前提で探す
 seek       | 見えないものを探す
 lose       | 見失う
 apply      | 登録する（要審査）
 register   | 登録する（確定）
 unregister | 登録を取り消す
 configure  | 設定する
 cancel     | 解除する


#### 操作の許可
 単語      | 意味
-----------|------------------
 allow     | 許可する
 deny      | 許可しない
 permit    | 厳密に許可する
 prohibit  | 厳密に禁止する
 accept    | 要求を承認する
 grant     | 権限を与える
 enable    | 利用可能にする
 disable   | 利用不可にする
 commit    | やる（確約する）
 omit      | やらない
 recognize | 存在を認める
 ignore    | 無視する

#### 状態の変更・データ操作
 単語            | 意味
-----------------|--------------------------------------------
 attach          | 結びつける
 detach          | 切り離す
 suspend         | 休止する
 resume          | 復帰する
 enable          | 有効にする
 disable         | 無効にする
 optimize        | 最適化する
 normalize       | 正規化する
 brief           | 要約する
 supplement      | 足りないものを補う
 complement      | 相互補完する
 merge           | （複数を）統合してひとつにする（分解不可）
 combine         | 混ぜる・組み合わせる（分解可）
 separate        | （混ぜ合わせたものを）分ける
 divide          | （ひとつのものを正確に）分ける
 split           | 分割する（主に文字列）
 slice           | （配列やリストから）切り出す
 trim            | （両端の余分な空白等を）取り除く
 share           | 分け合う
 dedupe          | 重複を排除する
 replace         | 置き換える（継続的な意味合いがある）
 substitute(sub) | 置き換える（一時的な意味合いがある）


#### プロセス・処理
 単語        | 意味
-------------|------------------------------
 preprocess  | ～の前処理をする
 postprocess | ～の後処理をする
 deprocess   | ～の戻し処理をする
 process     | ～を処理する
 undo        | 操作を取り消す
 redo        | 操作の再実行
 start       | 動き始める  対：stop
 stop        | 止める
 begin       | 開始する  対：end
 break       | 中断する
 abort       | 異常終了する
 finish      | 段階的に終わる
 end         | 完結する
 begin       | 状態を開始する
 quit        | 状態から離れる
 exit        | 状態から抜ける
 open        | プロセスを開く
 shut        | プロセスを閉じる
 call        | ～を呼び出す
 execute     | ～を内部的に実行する
 run         | ～をユーザが実行する
 eval        | ～を式として評価して実行する


#### 状態の確認
 単語             | 意味
------------------|----------------------------------
 affirm           | ～が本当であることを確認する
 check            | ～であるかを確認する
 confirm          | ～が真実であることを確認する
 identify         | ～が本物であることを確認する
 validate         | ～が要求にあっているか検証する
 seal             | ～が決定事項であることを確認する
 is_null          | NULLか
 is_empty         | 空か
 is_null_or_empty | NULLまたは空か
 is_valid         | 有効か
 is_enabled       | 利用可能になっているか（静的）
 is_available     | 利用可能になっているか（動的）
 is_visible       | 表示状態か
 is_ready         | 準備はできているか
 can_run          | 実行可能か(ユーザ）
 can_execute      | 実行可能か（内部処理）
 can_save         | 保存可能か
 can_close        | 閉じることが可能か
 has_saved        | 保存済か
 has_changed      | 変更されているか
 has_next         | 次があるか
 has_previous     | 前があるか
 is_normal        | 正常な状態か
 is_no_error      | エラーがないか


#### 比較
 単語          | 意味
---------------|------------------------------------------
 compare       | 比較する。（大＝1、等しい=0、小さい=-1）
 is_same       | 同じか
 is_correlated | 相関関係があるか
 is_similar    | 似ているか
 is_match      | 条件・特徴が一致しているか
 is_big        | サイズが大きいか
 is_small      | サイズが小さいか
 is_max        | 最大か
 is_min        | 最小か
 exists        | 存在しているか
 contains      | 含むか
 equals        | 等しいか
 eq            | 等しいか
 ne            | 等しくないか
 is_under      | より小さいか
 lt            | より小さいか
 is_over       | より大きいか
 gt            | より大きいか
 is_or_under   | 以下か
 le            | 以下か
 is_and_over   | 以上か
 ge            | 以上か
 is_many       | 多いか
 is_few        | 少ないか
 is_wide       | 幅が広いか
 is_narrow     | 幅が狭いか
 is_high       | 高さが高いか
 is_low        | 低いか


#### ログイン・認証
 単語           | 意味
----------------|------------------------
 log_in         | ログインする（UNIX)
 log_on         | ログインする（Windows)
 sign_in        | ログインする（Web)
 log_out        | ログオフする（UNIX)
 log_off        | ログオフする（Windows)
 sign_out       | ログオフする（Web)
 sign_up        | アカウントを登録する
 sign_on        | 書類にサインする
 certification  | 第三者が証明する
 authentication | 本人認証する
 identification | 本人確認行為
 identifier     | 本人情報
 identity       | 本人特徴情報


#### ネットワーク・コネクション
 単語       | 意味
------------|------------------
 connect    | 接続する
 disconnect | 切断する
 download   | ダウンロードする
 upload     | アップロードする
 request    | リクエストする
 respond    | レスポンスを返す

#### その他
 単語           | 意味
----------------|--------------------
 uc(upper_case) | 大文字にする
 lc(lower_case) | 小文字にする
 show           | 表示する
 hide           | 非表示にする
 collapse       | 折りたたむ
 expand         | 展開する
 toggle         | 切り替える
 turnOn         | オンにする
 turnOff        | オフにする
 classify       | 分類する
 predict        | 予測する
 adjust         | サイズにあわせる
 adapt          | 環境にあわせる
 draw           | 描く
 erase          | 消す
 up             | 上がる
 down           | 下がる
 next           | 順番の次へ
 previous       | 順番の前へ
 go             | 前へ進む
 back           | 後ろに下がる
 comment        | コメントする
 uncomment      | コメントを解除する
 via            | ～を経由して
 from           | ～から


#### 位置関係
 単語1      | 単語２      | 単語３     | 意味
------------|-------------|------------|--------------------------------------
 src        | dest        | －         | 送り元／行き先
 source     | destination | －         | 送り元／行き先
 left       | center      | right      | 左／中／右
 top        | center      | bottom     | 上／中／底
 before     | after       | －         | 前／後
 front      | back        | －         | 前側／後側
 forward    | backward    | －         | 前面／背面
 foreground | background  | －         | 前景／背景
 ahead      | on_schedule | behind     | 予定より早い／予定通り／予定より遅い
 next       | current     | previous   | 次／今／前（時間軸）
 in         | out         | －         | 中／外
 north      | south       | －         | 北／南
 east       | west        | －         | 東／西
 under      | over        | －         | 下回る／上回る
 or_under   | and_over    | －         | 以下／以上
 old        | new         | －         | 旧／新
 first      | last        | －         | 最初／最後
 min        | average     | max        | 最小／平均的／最大
 yes        | no          | －         | はい／いいえ
 head       | tail        | －         | 頭／尾
 large      | small       | －         | 大きい／小さい
 big        | small       | －         | 大きい／小さい
 parent     | child       | children   | 親／子／子どもたち
 others     | sibling     | self       | 他人／（男女別なし）兄弟／自分
 ancestors  | descendants | －         | 先祖／子孫
 header     | body        | footer     | ヘダー／ボディ／フッター
 server     | client      | －         | サーバー／クライアント
 kind       | class       | type       | 大まかな種類／階級／一般的な種類
 grade      | level       | rank       | 等級／水準／順位
 config     | setting     | preference | 構成設定／ソフト設定／表示や挙動設定


#### 状態
 単語1      | 単語２      | 単語３    | 意味
------------|-------------|-----------|------------------------------------
 open       | closed      | －        | 開いている／閉じている
 old        | new         | －        | 古い／新しい
 prefix     | suffix      | －        | 接頭／接尾
 dry        | wet         | －        | 乾いている／湿っている
 past       | now         | future    | 過去／現在／未来
 permission | prohibition | －        | 許可／禁止
 fast       | slow        | －        | 速い／遅い
 quick      | slow        | －        | 素速い／遅い
 good       | bad         | －        | 良い／悪い
 same       | different   | －        | 同じ／違う
 normal     | abnormal    | －        | 正常／異常
 normal     | error       | －        | エラーがない／エラーがある
 regular    | irregular   | －        | 規則的な／不規則な
 general    | specific    | special   | 一般的／特定の／特別な
 usual      | unusual     | －        | いつもの／日常的ではない
 ordinary   | special     | －        | 普通の／特別な
 common     | uncommon    | －        | 共通の／共通でない
 visible    | hidden      | －        | 表示状態／非表示状態
 valid      | invalid     | －        | 有効な／無効な
 enabled    | disabled    |           | 利用可能な／利用不可能な(静的）
 available  | unavailable | －        | 利用可能な／利用不可能な（動的）
 provider   | user        | －        | 提供者／使用者
 host       | guest       | －        | 招く側／招かれた側
 caller     | callee      | －        | 発信する側／される側
 on-premise | cloud       | －        | 自社システム／クラウドサービス
 expression | formula     | －        | 評価式／公式
 equation   | inequality  | －        | 方程式／不等式
 limits     | bounds      | range     | 制限内／境界／範囲
 act        | action      | behaivior | 単一行動／集団行動／振る舞い・態度
 correct    | right       | －        | 明確な基準で正しい／一般的に正しい
 unknown    | misc        | －        | 未知の／雑多な
 required   | reserved    | diversity | 必須の／予約された／多様な
