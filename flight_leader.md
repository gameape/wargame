# Flight Leader

## コマの読み方

- 左上：旋回タイプ（A～F）、大文字=大型機、小文字=小型機 / H=高加速、N=通常加速、大文字=アフターバーナー
- 右上：レーダー / カウンターメジャー、ドットの数 = クルーの数、白丸はバブルキャノピー
- 左下：ミサイルレール / 内蔵兵装 C=キャノン（射程1）、M=マシンガン（射程1）、なし=外部兵装可、白丸=兵装修整あり

## プレイの手順

- エントリフェイズ
  - 自軍盤端の4ヘクス以内のヘクス（複数可）に配置、競合DRが小さい側が先、7ターン及びより後は進入不可（9.4.1.7）
  - 配置/進入時に全航空機はエレメントに編成され、フォーメーションに属し、必要なビジュアルコンタクトを持っている（10.2）
- イニシアティブ決定フェイズ
  - スピード+高度の大きい機が先、同じなら、フォーメーションにいる機が先、同じなら、タリー/ロックオン持ちが先、同じなら、競合DRの大きい航空機が先
- コンタクトフェイズ
  - スポット or ロックオン：シングルシーターのパイロット、2シーターのセカンドクルー
  - スポット：2シーターのパイロット
  - スポット
    - クルーごとにある1個のクワドラント内で無制限回のタリー試行/維持と、ある1個のクワドラント内で無制限回のビジュアル試行/維持ができる
    - 2シーターの一方のクルーがスポットしたら、もう一人もただちにスポットする
    - スポットは禁止事項に該当しなければ自動的に維持
  - スポット禁止事項
    - 低高度かつ後方クワドラント
    - 同/低高度かつ旋回方向の逆の側方クワドラント
    - 2シーターのパイロットかつ非バブルキャノピーかつ後方クワドラント
    - ロックオン試行中のクルーによるタリー試行
    - ルート/フィンガーティップ/トレイルフォーメーションの制限
    - スポッティングレンジ外
    - 同一ヘクスかつ低高度
  - ロックオン
    - 前クワドラント
    - レーダー値が5以下なら1機、5より大きければ何機でも
- 移動フェイズ：航空機ごとに飛行決定ステップとアクションステップ or 飛行決定ステップを秘密裏かつ同時に
  - 飛行決定ステップ
    - スロットル設定：AB、MIL、IDLEから選ぶ
    - 燃料：ABなら2、MILは1を消費、Bingo（1です、注意）になるならやり直し
    - マヌーバー決定：9個（CL、C、CR、L、A、R、DL、D、DR）から好きなものを
    - 高度変更決定：Aheadでは0、Climb/Diveでは±1～6
    - 高度変更：現在の高度に高度変更を反映
    - スピード変更決定：加速表でスピードの増減を求めて現在スピードに反映
      - 加速表がP/変更後の現在スピードが3または変更する高度レベルより小さければやり直し
      - 現在スピードはMSより大きくならない（要確認）
      - SubsonicかつMILかつ高度変更なし or NormalかつABかつ高度変更なしなら+1ではなく0にできる（17.9）
  - アクションステップ
    - スピード値から高度変更値を引いた数と等しいヘクス数を移動、途中で射撃可、オートスポット可
    - マヌーバーがL/Rなら該当方向に要旋回、ターンモード表が示すヘクス数を直進するごとに60度旋回可、スピードを失えば急旋回可
    - 高度変更は最初の移動先ヘクスに進入する前に発生
    - スタック制限なし、空中衝突なし
    - コマはヘクスサイドに向ける（旋回は60度単位）
    - プランドルート飛行の制限
      - CAPは開始ヘクスの8ヘクス以内
      - 高度変更は最大1/ターン
      - 上級マヌーバー不可
      - フォーメーションにとどまる
      - 移動後に旋回によるスピード喪失を適用、最後に旋回した側にマヌーバーを変更
  - ターン記録 / 勝利判定フェイズ