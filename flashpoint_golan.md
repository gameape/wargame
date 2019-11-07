# Flashpoint: Golan（未完成）

## ユニットの読み方
- 地上ユニット（裏面はDisorganized）
  - 戦闘力
  - 砲兵：戦闘力 射程
  - HQ：戦闘力 指揮範囲
  -	カッコつき戦闘力は防御のみ
- 航空ユニット：ストライクレーティング ストライク修整

## プレイの手順
### 戦略サイクル
1. イニシアティブ&政治イベントフェイズ
  - モメンタムポイント優位の方がイニシアティブ（0ならイスラエル）
  - モメンタムポイント50ポイントごとにボーナス・アクティベーション1個
2. 制空フェイズ
  - 制空レベル決定（イスラエル3～ニュートラル～アラブ3）
  - 空襲回数決定
3. ジャミングフェイズ
  - 1HQにつきレンジ内の1HQをジャミング可（dr≦6+過去の実施回数（イスラエル最大+3、アラブ+5）で成功）
4. 増援フェイズ
  - モビライズ：HQを表の面に、ユニットをHQまたは隣接ヘクスに配置、活性化は次のターンから
  - 増援：そのターンから活性化、同一ヘクスにn番目に進入するユニットは進入ヘクスの移動コストがn倍
5. 補給&再編成フェイズ
  - HQはLOC設定可なら補給下（友軍マップ端 or 自国にある都市に続く道/ハイウェイの4ヘクス以内、EZOC、敵ユニット、Impassable、不参戦国領土、道なしのEscarpment/Mountain Ridge/Mountain不可）
  - ユニットは補給下のPrimary/Command HQのIn Command（Command Radii内、友軍なしEZOC、敵ユニット、道なしEscarpment/Mountain Ridge/Mountain不可）なら補給下
    - LOCとCommand Radiusが微妙に違う。Command RadiiもImpassable不可では？
  - 補給切れ：HQはただちにモラル-1、ユニットは攻撃力1/2（切り捨て）、Mech/Motorは3OP、攻撃はSmall、砲兵は最初のサポート/ストライクの後Ammo Depletionに
  - Replenish Supply（OOSを除去するということ？）
  - Reorganize
    - ユニットはIn Commandで非EZOC、HQはLOCで非EZOCならReorganizeマーカー
    - マーカー除去：移動、撤退、バトル参加、ストライク実施、ストライクでモラル低下、EZOCに入る
  - Replenish Artillery Ammunition

### 作戦サイクル
- イニシアティブプレイヤーは自軍の活性化チット1個を選んで隠し持つ
- 活性化セグメント
  1. 移動フェイズ
  - EZOCにいる活性化ユニットの
    - 撤退（2ヘクス後退してモラルチェック）
    - Hold Position（攻撃しない）
    - Set-piece Battle（EZOC及ぼし元をすべて攻撃）
  - EZOCにいない活性化ユニットの移動とMeeting Engagement
  - 活性化プレイヤーの航空補給、両軍の砲兵弾薬補給
  2. 拡大（Exploit）移動フェイズ
  - EZOCにいる活性化ユニットの撤退、Hold Posiotion、Set-piece Battle
  - Breakthroughマーカーの5ヘクス以内で非EZOCな活性化ユニットの移動とMeeting Engagement
  - 活性化プレイヤーの航空補給、両軍の砲兵弾薬補給
### 終了サイクル
- マーカー除去：Breakthrough、Struck、Ops Comp、Reacted、HQ Capability、HQ Disrupt
- Air Stikesマーカーを0に
- Reorganizeマーカー除去＆ユニットはモラル1上昇、HQはCapability Replacement Point消費でモラル上昇
- 1ターン以上前に除去されたHQをCapability Replacement Point消費で友軍HQヘクスにCadreで復帰
- ターンマーカー前進
- HQ能力消費マーカー除去

## Troop Quality / 訓練レベル
- 訓練レベルとdrでTroop Qualityを決める

## スタック
- 6個大隊、移動/突破フェイズ終了時に判定、丘/山/通行不可は機械化/自動車化は4個大隊まで
- 旅団=連隊、旅団=3個大隊、タスクフォース=2個大隊
- （スタックのみ）砲兵連隊/旅団は2個大隊相当、HQは数えない

## ディテクト
- ディテクト・アセット：非DisruptのHQ、Disorganized+の戦闘ユニット

## 砲兵

## HQ Capability
- 航空補給：航空補給能力のレンジ内にいる1個旅団を補給、友軍移動/拡大移動Phまたは補給&再編成Ph
- 砲兵弾薬補給：In Commandな大隊規模の砲兵ユニット1個を弾薬補給、移動/拡大移動Phまたは補給&再編成Ph
- 前線回復：バトル（ストライクではない）でモラル減少を被った勝者側の1個旅団相当がそのモラル減少を無視、戦闘解決直後
- 戦闘工兵：
- HQ探知：HQ探知能力のレンジ内で能力を使ったHQを探知、HQが能力を使った直後
- ジャミング：ジャミング能力のレンジ内の敵HQをジャミング、ジャミングPh
- 戦車輸送：
- ヘリコプター輸送：
- 航空防御砲兵：
- 対戦術弾道ミサイル：
- 巡航短距離弾道ミサイル：
- 艦砲射撃：

## その他
- 10面体ダイス、10ではなく0
- 4km/ヘクス、1日/ターン
