# プログラミング応用
名古屋工業大学情報工学科3年 プログラミング応用講義資料 テンプレートマッチング課題用データセット

講義内容は下記リンクで移動してください．
[講義のページ](https://github.com/fukushimalab/advanced_programming)

## 最終データセット

最終テスト用のデータセットが20種類で合計1.67GBあるため本体から分離しています．
finalにコピーして使ってください．
どれでテストするかは，テストの当日に発表します．

なお，各画像はpngで圧縮されています．
適切に処理してください．

## ディレクトリ構成
* final_dataset
  * dataset1
    * image
      * level1
      * ...
      * level7
  * ...
  * dataset20
  * template_1to10 (dataset1から10用のテンプレート画像)
  * template_11to15 (dataset11から15用のテンプレート画像)
  * template_16to20 (dataset16から20用のテンプレート画像)
* DatasetGenerator
  * 新しく作るためのコードです．本講義中は使いません
