# Welcome to the NGPL wiki!  
  
I have to say sorry about this project is written in Japanese programing language, "Nadesiko(なでしこ)",  
so you may be cannot hack this project.  
But... if you are highly motivated, we are welcome you !  
  
**N**adesiko **G**ame **P**rograming **L**ibrary  
======================  
なでしこ製ゲームプログラミングライブラリ  

* チュートリアルに  
* アルゴリズムのテストに  
* 動的な図解やアニメーションに  
  
   最高のパフォーマンスを提供します。  
 
 
使い方
------
 
### NGPLによるコーディング
  
NGPLはとてもシンプルに設計されています。  
現在はほとんどの機能が開発中ですが、ユーザーにとって直感的で分かりやすいインターフェイスを提供します。  
  
以下はそのコーディングの例です。  
  
    GPLInit()                              # NGPLの初期化
    GPLBufferScreenParam(0,0,400,200,0)    # x,y,w,h,色で、バッファスクリーンを初期化する
    BufferScreen→InitUserColor($ff0000)    # ユーザーの任意のカラーで高速画面クリアをするための初期化 (イメージ１つ分のメモリを消費する)（オプション）
	
    AをGraphic_gとして作成                     # ユーザーが使う際はGraphic_gを継承する
    BをGraphic_gとして作成
    A→Load(`Magicsquare_b.bmp`)            # メモリに画像をロードする。(bmpのみ)
    B→Load(A→Same())                       # Aと同じ画像を使ってロードする。
    B→x = 100
    
    # ループではここから開始
    # バッファー画面のクリア
    BufferScreen→UserClear()
	
    # グラフィックオブジェクトの描画
    A→Draw()
    B→Draw()
	
    # バッファを可視画面にフリップして、バッファは消去する。（DONTCLEAR==1ならば消去しない）
    BufferScreen→Flip()
	
    # グラフィックオブジェクトの破棄
    A→Delete()
    B→Delete()

これはGPLのメインファンクションが記述されているソースコードに付属するほんのサンプルです。  
なでしこそのものがとてもシンプルに設計されていますが、いざゲームを作ろうとすれば思いの外必要なものが多いことに気付くでしょう。  
  
この中では汎用性を持たせながらも、さり気なく便利な機能を多数搭載しています。  
NGPLでは標準として以下の機能を提供します。  

## 標準機能 ##

    1. ダブルバッファリング  

    2. イメージの高速描画

    3. イメージの回転・拡大描画

    4. イメージの色抜き描画

    5. フレーム間隔制御(FPSの固定)

    6. オブジェクト同士の当たり判定

    7. 曲線系関数


  
関連情報
--------
  
* [GAMERSLIB](https://sites.google.com/site/tatumakiprojectn1/sakuhin/tatumakigen/game-s-library "GAMERSLIB")  
GAMERSLIBはこのプロジェクトの前身となるライブラリです。  
これらのライブラリをより使いやすくし、ゲーム用途に特化させたものがNGPLとなります。  
  
