どんな処理にしたか
画像を読み込み画像のサイズが大きい場合縮小操作を行う。 
次に、画像をグレースケールに変換しフーリエ変換をする。 
左上にグレースケールの元画像、中上と中下にパワースペクトル、左下にクリックしたサイン波を重ね合わせていったものを表示し、右下にリアルタイムでクリックしたところのサイン波を表示する。 
そして、マウスイベントごとにコードを設定しサイン波を更新するようにする。

依存ライブラリとバージョン
numpy(1.16.2),Pillow(5.4.1),matplotlib(3.0.3)

参考にしたサイト
十河研究室、Windows用Portable PsychoPy / VisionEgg
http://www.s12600.net/psy/etc/python.html

Python NumPy SciPy サンプルコード: フーリエ変換処理 その 1
https://org-technology.com/posts/fft-01.html

pythonで「二次元フーリエ変換をした後、象限を取り換える」関数を作った
http://naga-tsuzuki.sblo.jp/article/181973347.html
