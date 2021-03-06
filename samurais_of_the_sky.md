# Samurais of the Sky

## コマ
[![Samurais of the Sky](https://farm1.staticflickr.com/835/29226942078_eb198b8b1a_z.jpg "Samurais of the Sky")](https://www.flickr.com/photos/22264692@N00/29226942078/)

## 値ごとの用途
- Sf（Speed）：移動力決定
- Mf（Manoeuvre）：機動カードの成否判定
- Ef（Engine）：加速可否判定
- Bf（Break）：減速可否判定
- Ff（Fire）：射撃命中判定
- Df（Defense）：射撃被害判定

## プレイの手順

- 計画順決定
- 計画
- 飛行順決定
- 飛行、射撃
- 10ターン終了ならゲーム終了。そうでなければ次のターンへ。

## 計画順決定
1. 高度がより低い機が先
2. 同じならPLがより低い機が先
3. 同じなら連合軍が先

## 計画
1機目の全ステップ完了後に2機目、3機目…と進める
1. 姿勢を降下、水平、上昇から選ぶ
2. 加速するならEf判定（水平、上昇のみ可）
3. 移動力決定（端数切り捨て）
  - 上昇  （Sf+高度修整）×0.5＋加速成功なら+1
  - 水平  （Sf+高度修整）＋加速成功なら+1
  - 降下  （Sf+高度修整）×1.5
4. 機動計画
  - 機動カード0～2枚を選択（姿勢制限に合致するもののみ）
  - 残移動力=移動力-機動カード記載の移動力合計
  - 残移動力が0未満になる機動は不可

## 飛行順決定
1. 残移動力がより大きい機が先
2. 同じならPLがより大きい機が先
3. 同じなら日本軍が先

## 飛行
1機目の全ステップ完了後に2機目、3機目…と進める
1. 高度変更
2. 移動
  - 残移動力を1消費して直前方ヘクスに向きを変えずに進入、または
  - 機動実施、または
  - 減速（1ターンに1回だけ、Bf判定、通常でMA-1or2、損傷でMA-1）、または
  - 射撃

## 射撃
- 射撃実施条件
  - 目標は同一ヘクスかつ同一高度の敵機
  - 移動前は射撃不可、1ヘクス以上移動した後に（移動途中でも）射撃可
  - 1ターンに1回だけ射撃可
- 命中判定はFf
  - 進入方向DRM（0時：-3、2時と10時：-4、4時と8時：-1、6時：0）
  - 目標移動済：-1
  - 射撃機が移動終了ヘクスで射撃：+1
- 被害判定はDf、成功で損害、失敗で撃墜
  - 命中判定のFf-drの値がDRM
