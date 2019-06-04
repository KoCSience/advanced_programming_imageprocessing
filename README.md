# プログラミング応用
名古屋工業大学情報工学科3年 プログラミング応用講義資料 テンプレートマッチング課題用プログラム

[説明資料（途中で読み込みが止まるので，右クリックしてダウンロードを推奨）](./advanced_programming_signal_processing.pdf)

## 達成目標
ある目的を達成するには，すべての機能を一つの言語だけでプログラムする必要はない．

本課題では，画像処理において，特定の画像が入っているかどうか検査するテンプレートマッチングを，以下3つの機能を組み合わせることを実現する．

* c言語プログラム
* ImageMagick
* シェルスクリプト


C言語プログラムでは，テンプレートマッチング自体が実装してある．
ImageMagickは簡単な画像処理を行う，コマンドラインベースのプログラムである．
シェルスクリプトは，上記二つをうまく呼び出すように結合されコマンドを連続で打つためのスクリプトである．

それぞれを工夫することで，最短時間で高い検出率を達成することを目指す．

## マニュアル
テンプレートマッチングを実行

`time sh run.sh level2`

結果をチェック

 `sh answer.sh result level1`

## ダウンロード方法

![ダウンロード方法](./image/fig1.png "ダウンロード方法 ")