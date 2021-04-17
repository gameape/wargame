# 賤ヶ岳戦役

## 駒

### 駒の分類
- 駒 には 軍勢 と マーカー がある
- 軍勢 には 軍勢駒 と 守備隊 がある
- 軍勢駒 には 指揮官 と 足軽（兵士2名のシルエット） がある
- 指揮官 には 大将（軍配持ちのシルエット） と 部将（馬に乗ったシルエット） がある
- 黒線が 羽柴方 で、赤線が 柴田方

### 駒の読み方
- 指揮官の数値は上が攻撃力、下が行動力
- 守備隊の数値は攻撃力
- 軍勢は表面が通常状態、裏面が損耗状態
- 旗印が同じなら、同じ大名家所属

## 地形と陣地マーカー
|種別|移動コスト|戦闘|備考|
|:-----|:----:|:----|:----|
|平地|2|影響なし||
|丘陵|3|丘陵から平地を攻撃/反撃なら攻撃力+1|丘陵と平地を含むヘクスは丘陵|
|山地|禁止|不可|山地を含むヘクスは山地|
|海|禁止|不可|琵琶湖も海|
|城塞|2|退却/反撃が先||
|京|2|影響なし||
|河川|+3|攻撃反撃とも駒数×1/2（端数切捨）|河川越えの退却は移動力チェック|
|街道|1|影響なし|OT無効化|
|盤外|2|禁止|スタック制限なし、柴田方は羽柴方盤外に進入不可|
|陣地|影響なし|退却/反撃が先|敵進入なら除去|

## プレイの手順
- 羽柴方、柴田方の順に以下の手順を1回ずつ実施して1ターン終了
- 任務数決定（柴田1d、羽柴1d+2）
- 任務の割当（任務数の指揮官に任務割当マーカーを載せる）
- 戦意向上（所属大名家の参戦マーカーを任意の方向に1列動かす）
- 回復（行動力に等しい数の、任務実施指揮官と同じヘクスにいる、自身と同じ大名家の指揮官とスタックしているユニットを通常状態にフリップできる、守備隊もフリップできる、EZOCなら不可）
- 陣地構築（任務実施指揮官と同じヘクスの陣地を1レベル上昇、1ターンに1ヘクスを2レベル上昇させるのはNG、EZOC不可）
- 作戦行動（全指揮官の移動の後に、全指揮官の野戦、その後に全指揮官の攻城戦）

## 連絡線
- 所属陣営の守備隊が存在する城塞までのヘクス経路
- 進入不可ヘクス/ヘクスサイド、EZOC、敵軍勢が遮断
- 攻撃力、行動力を使う時点で判定、設定できなければ攻撃力、行動力が-1

## 行動力
- 行動力=1：作戦行動の移動、野戦、攻城戦のうち1つだけ可
- 行動力=2：作戦行動の移動、野戦、攻城戦のうち2つだけ可（1つ実施したら任務割当マーカーを裏返す）
- 行動力=3：作戦行動の移動、野戦、攻城戦の全部可

## 移動
- 移動力を指揮官ごとに1d+行動力で決める
- 大将は自分含め8駒、部将は自分含め4駒を引率可、部将は大将を引率不可
- 移動途中に軍勢駒を拾う/落とすは不可、軍勢駒は1ターンに1回だけ移動可
- 最低1ヘクス移動なし

## ZOC
- 軍勢の周囲6ヘクス
- 進入したら移動終了、退出コストなし、ZOC to ZOC可

## スタック
- 軍勢駒8個
- 移動、退却、戦闘後前進終了時に判定
- 超過時は指揮官が制限を満たすように退却
- 盤外ヘクスはスタック制限なし

## 野戦
- 指揮官ごとに目標1ヘクスを宣言して軍勢駒を攻撃、複数の指揮官で1ヘクスを攻撃可
- 引率されている軍勢駒は同じ目標を攻撃
- 手番プレイヤーの攻撃、非手番プレイヤーの退却/反撃の順で解決
- 陣地/城塞では非手番プレイヤーの退却/反撃が先
- 通常状態の軍勢駒の数だけdr、攻撃力以下で1駒損耗（通常面不在なら1駒除去）
- 攻撃をおこなった指揮官ごとに攻撃継続/終了を選択、継続なら攻撃解決に戻る

## 攻城戦
- 守備隊を攻撃する場合は攻城戦
- 攻撃はdr=1で損害（反撃は野戦と同じ）

## 退却
- 1ヘクス、スタック制限超過なら追加1ヘクス
- 最も近い守備隊から遠ざかる退却は不可
- EZOCに退却なら損耗チェック
- dr+行動力が必要な移動ポイント以上でなければ河を渡る退却は不可

## 損耗
- 退却後、第1～4ターンの豪雪地帯での移動後に軍勢駒の数のダイスをふり、dr≦2の数だけ損耗

## 参戦トラック
- 状況マーカー：部将除去で1、大将除去で2、城塞陥落で1
- 参戦マーカー：戦意向上で1、守備隊/足軽除去で1

## 勝利条件
- 柴田勝利：羽柴秀吉除去 or 柴田方が京を支配 or 第18ターン終了時に状況マーカーが柴田勝利またはより左
- 羽柴勝利：柴田勝家除去 or 羽柴方が北国盤外ヘクスに進入 or 状況マーカーが羽柴勝利に到達
- 第18ターン終了時にいずれの条件も達成されていなければ、条件を達成するまでプレイ