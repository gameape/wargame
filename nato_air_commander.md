# NATO Air Commander

## コマの読み方
- 左上のSはステルス、右上が損失ナンバー
- 下は左から航空 - 地上 - 攻撃
- 青 = US、タン = イギリス、金 = ドイツ、赤 = カナダ、オレンジ = オランダ、黄 = ベルギー
- 陸上兵力コマの数字はコヒージョン、上を向いているのが現在の値

## 解決カード
- ユニットの値がカードの値未満なら成功、以上なら失敗

## 目標受領フェイズ：
- 目標カード2枚引いて見る
- シャッフルならこのターンにドローしたカードを含めてシャッフル
- 再びシャッフルならディスカードして、もう1枚の目標だけ有効に

## 偵察フェイズ
- ユニットは使わず、値6 （OCAで修整）でAir Intercept解決
- Battlefield Surveillance：ターンに1回のみ、解決カード1枚ドローしてイベント発動 or デッキの底に
- Locate Headquater：ターンに1回のみ、DECAP STRIKEマーカーを置く
- Locate Staging Areas：Thrust Lineごとにターンに1回、増援カードをフリップ（FOFAが可能になる）
- 失敗するまで何度でもできる

## 航空計画フェイズ
- プライマリミッションに最大3ユニット、1レイドに最大5ユニット
- ひとつのボックスまたはトラックに最大3レイド/ターン
- OEWミッション：航空値が1以上の最大2ユニットをアサイン可、必ず成功、OCAマーカーを一時的に1個右に

### PGM
- ユニットごとに1個アサイン可
- アサインされたユニットの値が2倍
- レイド終了時に除去

### パイロット
- レイドごとに最大1個の、ユニットと同じ国籍のパイロットをアサイン可
- アサインされたレイドのミッション（アサインされたユニットが関わっていないミッションでも可）解決にもう1枚カードを引いて選べる、使用後除去
- アサインされたユニットが損害を受けたら除去

### ステルス
- 単独ならAir Interceptなし、Ground DefenseはAir Intercept and/or Ground Defenseが10なら除去

## レイド解決フェイズ
- 好きな順番で、先に解決されたレイドの結果は同じターンの後のレイド解決に影響する
- 航空阻止セグメント（航空護衛ミッション解決、Air 対 Air Intercept、OCA修整）
- 地上防御セグメント（SEADミッション解決、Ground 対 Ground Defense、DEAD修整）
- プライマリ・ミッション結果セグメント（5ポイントごとに1ヒット、切り捨て、最低1）
  -  近接航空支援（CAS）：Ground、目標Thrust Lineの地上戦闘を修整
  - Follow-on Force Attack（FOFA）：Ground、偵察によるLocateが必要、目標Thrust Lineの増援値をヒット数だけ削減
  - Destruction of Enemy Air Defenses（DEAD）：Strike、DEADマーカーをヒット数だけ右に、最大3/ターン
  - Offensive Counter-Air（OCA）：Strike、OCAマーカーをヒット数だけ右に、最大3/ターン（OEWは含まず）
  - Decapitation Strike：Strike
    - DECAP STRIKEマーカーが必要
    - 1ヒット目：デッキまたはディスカードパイルから任意の1枚を除去
    - 2、3ヒット目：同じターンのレイド解決、地上戦闘、増援の解決カードを2枚引いて選べる
- 目標達成判定（成功の効果適用は地上戦闘解決後）
 
## 地上戦闘フェイズ
- Attack Resolve + 右端のNATOのCohesion + CASのHit数 と WPのCohesion を比較
  - NATO ≦ WP：失敗、右端のNATOを除去して、WP前進
  - NATO > WP：成功、WPのCohesionを1減らす
  - NATO > WP×2：反撃、WPのCohesionを1減らす、WP後退（不可ならCohesion追加-1）、右端のNATO前進、空いたFEBA BoxにCohesion=1のNATO置く
- 目標達成によるWPの退却はここで実施、退却できないWPはCohisionが2下がる
  - Cohesion減少は2じゃなくて1じゃないのかと思うが、NATOが勝てないので、とりあえず2でプレイするよ

## 増援フェイズ
- WP増援を加算（FOFAのヒット分を減ずる）
- 次ターン分のWP増援カードを置く
- NATO増援は1枚ドローして好きなようにわりふり
- 航空ユニットの増援配置

## イベントフェイズ

## リソースポイントフェイズ
- 1ポイント：Starting BoxにいるWP軍ごと、NATO支配の3VP都市ごと、DEADが右端、OCAが右端
- -1ポイント：航空ユニット回復、パイロット、PGM（3RP）

## ターン終了フェイズ
- 帰投、OEW分のOCA減少、Air Interceptが偶数ならDEAD-1、同じくOCA-1、20VP以上なら核戦争、1～6ターンは左端のWP軍ごとに1VP　

## 勝利条件
- 第10ターン終了時に14VP以下ならNATOの勝利、15VP以上ならWPの勝利
- 6本のThrust LineすべてでWP軍が左端に達した時点でWPの勝利
