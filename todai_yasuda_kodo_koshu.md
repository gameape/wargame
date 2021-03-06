# 東大安田講堂強襲

## ユニット
- 表が未使用面：攻撃力 - 防御力 - 移動力
- 裏が行動済み面：防御力
- 攻撃力にマル：隣接エリア攻撃可
- 右端に小さい数字：トラブル発生値（≦2dなら使用せず除去）
- 遊撃中隊：ガス筒で攻撃可
- 赤地の防御力：防御 & バリケード除去時に火災全除去 & 火災、火炎瓶、火炎放射器を無効化

## 放水車ユニット
- 以下すべて事前にトラブル発生チェック実施、失敗なら除去
- 制圧攻撃、攻撃、防御攻撃時は防御ポイント計算前に火災マーカー全除去
- 制圧攻撃、攻撃、防御攻撃されたら攻撃ポイント計算前に火炎瓶、火炎放射器、火災マーカー全除去
- 未使用面を行動済み面に裏返せば妨害ポイント計算前に火炎瓶、火災マーカー全除去

## 武装チット
|コマ|用途・最大枚数|制限|コマ数|
|----|----|----|:----:|
|![ガス筒](https://farm8.staticflickr.com/7862/45518524385_0bdf3e2e1e_s.jpg)|制圧攻撃2、攻撃2|遊撃中隊のみ、3≧2dでトラブル|29|
|![突入トンネル](https://farm8.staticflickr.com/7912/45518523905_fed15e44ea_s.jpg)|攻撃への防御1|設置は移動手番に、ターン≧1dで設置可|3|
|![延長放水](https://farm5.staticflickr.com/4894/45518524505_f8ba2d7d01_s.jpg)|撤去1|火災マーカー数+ターン≧1dで使用可、妨害ポイント計算前に火炎瓶 & 火災マーカー除去|7|
|![エンジンカッター](https://farm5.staticflickr.com/4820/32559117628_5bf2640c1f_s.jpg)|撤去1|3≧2dでトラブル|9|
|![火炎瓶](https://farm8.staticflickr.com/7833/45518524045_81c13f6594_s.jpg)|制圧攻撃2、攻撃2、妨害1|使用後は火災マーカーに|18|
|![舗装敷石](https://farm5.staticflickr.com/4846/45518524225_e4c625f591_s.jpg)|攻撃2||13|
|![火炎放射器](https://farm8.staticflickr.com/7850/32559117328_cde84977ff_s.jpg)|攻撃1、妨害1|工学部でのみ使用可、火災マーカー数+ターン≦1dで使用可、使用後は火災マーカーにorプールに戻す|3|
|![劇薬](https://farm8.staticflickr.com/7900/32559117498_0b03111176_s.jpg)|妨害+1|他の武装チットと併用可|3|

## プレイの手順
- 手番実施フェーズ（警視庁側が先手 パスパス終了）
  - 同エリア & 同所属+車両 or 同セクト & 未使用面ユニットで手番実施グループ1個を編成
  - グループの全ユニットで以下のいずれかを実施して行動済み
    - 制圧攻撃：隣接エリアを攻撃（できないユニットは参加不可）
    - 攻撃：同じエリアを攻撃
    - 移動：隣接エリア1MP、敵存在エリア2MP、民青エリア0MP、スタック分割不可、グループ内最大MA使用
      - 進入エリアの未使用面ユニットが防御攻撃（裏返らず）、目標は行動済み面扱い
      - 突入トンネル設置
    - プロットシートからマップに：1エリアの未使用面ユニットを何個でも、行動済みにならない
- 白兵戦フェーズ
  - 機動隊ユニット存在エリアの日大工兵隊、バリケード、セクトユニットを配置
  - 全共闘ユニット存在エリアの機動隊（車両除く）を回復
  - エリアごとにバリケード除去 & 検挙行動（順番は警視庁が決定）
 - ターン終了フェイズ
   - 未使用面に回復
   - 4T 日大工兵隊 & バリケード 修理
   - 全共闘チット補充（2d - ターン数 枚）
   - 4T 警視庁もチット補充（12枚）
   - 1T 2T カルチェラタン戦況変更、第7機動隊も1個扱い
   - 4T 警視庁再配置
   - 4T 護送ユニット復活

## スタック
- 最大スタック枚数 = 緑丸数字
- 武道小隊は制限対象外
- 警察車両（警備車、放水車）は2枚扱い
- 常時適用

## 制圧攻撃/攻撃の解決
- 攻撃ポイント = 2d + ユニット1個の攻撃力 + グループの残りユニット数 + 武装チットの能力値 + 火災マーカーの数（全共闘のみ） + 防御攻撃なら-2
- 防御ポイント = 2d + ユニット1個（あるなら必ず突入トンネル）の防御力 + 未使用面ユニットの数 + 火災マーカーの数（全共闘のみ）
- 武装チットの宣言は攻撃ポイント算出プレイヤーが先
- 損害ポイント ＝ 攻撃ポイント - 防御ポイント（0以下なら無効）

## 制圧攻撃/攻撃の損害（所有プレイヤーが決定）
- 損害1：未使用面を行動済み面に、行動済み面を後退
- 損害2：行動済み面を除去
- 全共闘は後退不可（余った損害ポイントは無視）
- できるだけ均等に適用（警察車両は集中適用可）
- 警察車両が退却する場合、同じエリアの機動隊ユニットも一緒に後退可
- 敵ユニット存在エリアは後退不可

## バリケード除去
- 警視庁の除去ユニット（未使用面、除く遊撃/車両） & チット（最大1枚）宣言
- 全共闘の妨害ユニット（未使用面） & チット（最大1枚＋劇薬1枚）宣言
- 撤去ポイント = 2d + 1ユニットの攻撃力 + チット + 残りユニット数
- 妨害ポイント = 2d + 日大工兵隊/バリケードの防御力 + チット + ユニット参加なら+1 + 火災マーカー数
- 除去ポイント = 撤去ポイント - 妨害ポイント（0以下なら無効）
- 日大工兵隊は除去ポイントだけ減、バリケードは4p以下でFlip、5pで除去

## 検挙行動（日大工兵隊/バリケードが不在の場合のみ）
- 未使用面の機動隊（車両、遊撃隊除く）の攻撃力に等しい全共闘ユニットを検挙ボックスに
- 2ユニット以上検挙する場合は機動隊1個も検挙ボックスに（護送）
- 検挙されなかった全共闘ユニット（行動済みも）は反撃または逃亡
- 反撃：攻撃力だけdrして6の数だけ機動隊を除去、反撃した全共闘は検挙
- 逃亡：移動力無視で機動隊のいないエリアを通って全共闘ユニットのいるエリアへ

## セットアップ
- 警視庁 全ユニットを3エリアに配置
  - 第1～5機動隊 = 各8、第7 = 2、第8 = 19
  - 同一所属の機動隊は同エリアに
  - 弥生門と西方門は車両不可
- 日大工兵隊、バリケード、全共闘チット数決定
  - 全共闘5、反帝2、ML2、社学5、第四2、核マル5、中核12、日大3、バリケード9
  - 余りバリケードはカップに
- 全共闘 全ユニット、日大工兵隊、バリケードを実線 or 破線エリアに配置
  - 配置各エリアは1ユニットだけマップに置き、残りはプロットシートに隠す
  - 1エリアには同一セクトのみ
  - 安田講堂上層階エリアは複数セクトOK
  - 第四インターは他セクトに混ぜてOK
  - 東大全共闘は安田講堂上層階エリア or 安田講堂内部エリアのみ
  - 東大青医連は医学部関連エリアのみ
  - 革マル派は5ユニットまとめて1エリアに配置
  - 日大工兵隊は破線エリア不可
- 警視庁初期移動
- 警視庁チット25枚引く
