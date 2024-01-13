<h1 align="center">リバーシゲーム - Reversi Game</h1>
<h2 align="left">リバーシの描画の概要 - Reversi drawing overview</h2>


# サンプル - Sample
<img src="https://github.com/inori77/ReversiGame/blob/main/img/demo.gif" loading="lazy" width="85%">


<h3 align="left">ゲームの初期化 - Initialize the game</h3>
　◽️reversi.canvas.js 内の関数

 ```
　・reversi.core.init …… リバーシゲームの最初の初期化
　・reversi.core.initClck …… 盤面クリックの初期化
　・reversi.core.strt …… ゲームの開始処理
　・reversi.core.btnStrt …… 開始ボタンの表示とクリック時の処理
 ```


<h3 align="left">配置可能マスの描画 - Draw a placeable square</h3>

　◽️reversi.canvas.js 内の関数

 ```
 ・reversi.canvas.drwEnblSqsAll …… 配置可能マスの全描画
 ・reversi.canvas.drwEnblSqs …… 配置可能マスを1つ描画
 ```


<h3 align="left">リバーシゲームのシステム - System of reversi game</h3>

　◽️reversi.reversi.js 内の関数

 ```
 ・reversi.reversi.init …… リバーシの盤面初期化・各種共通処理
 ・reversi.reversi.scnBrd …… 盤面の全マスに対して処理
 ・reversi.reversi.XYToI …… 盤面のXY位置を、配列の要素位置に変換
 ・reversi.reversi.clcScr …… 各プレイヤーの石数を計算
 ・reversi.reversi.skp …… 手番を飛ばす
 ・reversi.reversi.getPTyp …… プレイヤーの種類を取得
 ・reversi.reversi.scnLn …… あるマスを基点に指定方向に盤面を1マスずつ見ていく
 ・reversi.reversi.getEnblSqs …… 配置可能マスの配列を取得
 ・reversi.reversi.putTkn …… 石置き処理
 ・reversi.reversi.execRvrs …… 石置き処理
 ・nxt …… 手番を次に進行
```


<h3 align="left">ゲームの進行 - Progress of the game</h3>
　◽️reversi.core.js 内の関数

```
 ・reversi.core.clckBrd …… 盤面クリック時の処理
 ・reversi.core.doRev …… 裏返しの描画処理
 ・reversi.core.playSERev …… 石が裏返る効果音を再生
 ・reversi.core.updt …… リバーシゲームの手番の更新処理
```


<h3 align="left">エフェクト - Effect</h3>
　◽️reversi.effect.js 内の関数

```
 ・reversi.effect.putTkn …… 石を置く際のエフェクト
 ・reversi.effect.chngBrd …… 石を置いた際の盤面変更のエフェクト
```


<h3 align="left">COMの思考 - COM thoughts</h3>
　◽️reversi.com.js 内の関数

```
・comIn …… コンピューターの指し手を計算
```
