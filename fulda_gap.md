# Fulda Gap

## コマの読み方
- 陸上ユニット：攻撃力 - 防御力
  - MAは一律10
- 補給輸送ユニット：MA - 補給レンジ - 攻撃力 - 防御力（Z読み）
  - 表はstatic、裏はmobile
- 航空ユニット：Penetration/Strike Allowance（nは核武装可）

## プレイの手順
- JOINT AIR SUPERIORITY TURN
- SOVIET PLAYER-TURN
  - Nuclear Planning Phase
  - Nuclear Strike Phase
  - Initial Movement Phase
  - Combat Phase
  - Secondary Movement Phase
  - Reorganization Phase
    - Place or Remove IP
    - Remove Disrupt
- NATO PLAYER-TURN
- CONTAMINATION REMOVAL and GAME-TURN INDICATION

## オーバーラン（5.3）
- 3MP消費して戦闘
- 攻撃力×1/2（端数切捨）
- 2ユニットで同一師団効果
- 空いた目標ヘクスに全ユニットが前進

## 混乱（5.4）
- オーバーランでステップロスか退却
- 不可：移動、退却、攻撃、離脱
- ZOC -1レベル
- 補給範囲×1/2
- Air Defense Zone×1/2

## スタック（6.0）
- ユニット2個
- フェイズ終了時に判定

## ZOC（7.0）
- Locking：進入停止、離脱は戦闘かdisengagement（14.0）、退却不可
- Erastic：停止不要、2MPで離脱可、混乱すれば退却可
- 混乱ユニットとIPにいるユニットがErastic ZOC

## 同一師団（8.1-8.3）
- 攻撃力2倍：全ユニットが隣接する2ヘクスに
- 防御力2倍：全ユニットが2ヘクス以内に
- オーバーラン攻撃2倍：2ユニットがスタック

## Improved Position（8.4）
- 再編成フェイズに配置、除去
- 防御力2倍
- 移動、退却不可
- 退却値+2
- ZOC -1

## 戦闘（9.0）
- メイアタック
- 退却値は累積
- 退却は可能な限りカラヘクスへ
- 所有プレイヤーが退却路を決定

## Accelerated Assault（9.4）
- ソ連が攻撃を1～3シフト宣言できる
- 戦闘結果を適用後、戦闘後前進実施前に攻撃ユニットごとにdr≦シフト数なら1ステップロス

## 戦闘後前進（9.9）
- 退却路に沿って前進可能
- ZOC無視
- 敵壊滅なら1ヘクスだけ
- 防御側も前進可能

## 砲兵（10.0）
- 射程4ヘクス（敵隣接なら3ヘクス）
- LOSなし
- 砲撃目標は1ヘクス
- 砲撃解決はオーバーランCRTで
- FTF=敵に非隣接なら防御力を射程内の友軍の防御に
- 同一国籍の砲兵の6ヘクス以内にいると攻撃に使えない

## 補給（11.0）
- 判定は移動フェイズ開始時と戦闘の直前
- Static：Dump = 20MP、Transport = 10MP
- Mobile：Dump = 10MP、Transport = 補給不可
- 補給切れ = 戦闘力×1/2（切捨）
- Mobile Transport = MA5
- モード変更、Dumpの積み、おろし = 移動フェイズ1回
- Dump運搬中は移動コスト×2
- ベルギーとイギリスはマップ北端から20MP

## Covering Force Unit（14.2）
- 攻撃不可、移動不可
- 次の敵プレイヤーターン終了時に除去
- ZOCなし、Air Defense Zoneなし
- スタック制限に含めず
- 友軍とスタック時は防御力0

## 化学戦（15.0）
- 移動フェイズに宣言
- きっかり2ターン有効
- NATOのUTU 右2シフト
- ソ連の攻撃力と防御力×2

## 空軍（18.0）
- スタック2個まで（ECM機は対象外）
- P/Sポイントの消費
  - スタックしてAir Defense Zoneを移動する空軍ユニットは、それぞれP/Sポイントを消費する
  - ECM機は同一ヘクスの友軍のかわりにP/Sポイントを消費できる
- 18.43 1個の空軍ユニットが複数のECM機に助けてもらえるのって、ECM機がP/Sポイントを保持したままマップ上に留まっている状態？
- Soviet air from any friendly East Germany hex（18.2）はNATOユニットやZOCを含まない東ドイツならどこでも、でいいかな？

## ナイキ・サイト（18.54）
- マップ全域
- 5ヘクスにつき2P/Sポイント
- ソビエト軍進入で破壊
- 4個（端数切上）破壊ごとに2P/Sで進めるヘクス数が倍に

## 空軍戦闘（18.6）
- 隣接or同一ヘクスの敵をP/Sを消費して攻撃
- 第一移動Phならオーバーラン
  - 攻撃力そのまま、追加MP不要
- 戦闘Phなら通常攻撃（地上ユニットと共同可能）
- 残りP/S≧7なら印刷された値で攻撃
- 残りP/S≦6ならAir Strike Table使用
- 対空軍だけの防御力は砲兵×3、補給と空軍基地×4

## ヘリコプター（20.1）
- 移動力無限
- 敵ZOC通過 dr=1で1ステップロス
- 敵砲兵4ヘクス以内通過 dr≦3で1ステップロス
- 移動しなかった場合でも攻撃は受ける
- 同一国籍6ヘクス以内制限（10.41）適用外
