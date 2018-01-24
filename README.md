# LaTeX_NN
LaTeXでニューラルネットワークを実装しました．データはiris.csv,iris_random.csvのみに対応しています．
## 各スタイルファイルについて説明
### answer_nn.sty
推論フェーズで使います．花びらの長さやがくの長さから種を分類します．
### cost_nn.sty
学習時の誤差を求めます．
### evaluation_param_nn.sty
各パラメーターを更新します．
### load_sty_nn.sty
それぞれのstyファイルを読み込みます．
### main_nn.sty
学習フェーズと推論フェーズのコマンドを定義しています．
### ready_nn.sty
csvからデータを読み込み配列に格納します．
### show_nn.sty
各パラメータを表示します．
### util_nn.sty
活性化関数や配列へ代入するコマンドなどが定義されています．
### weights_nn.sty
重みの初期化や更新などを行います．

## 詳しい説明などについてはブログを見てください
[http://muscle-keisuke.hatenablog.com/entry/2017/12/22/114406](http://muscle-keisuke.hatenablog.com/entry/2017/12/22/114406)
