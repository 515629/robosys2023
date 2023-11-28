# robosys2023
# plusコマンド
[![test](https://github.com/515629/robosys2023/actions/workflows/test.yml/badge.svg)](https://github.com/515629/robosys2023/actions/workflows/test.yml)

## 何をするためのソフトウェアか
このソフトウェアは,標準入力から読み込んだ数字を足すもの

## インストール方法
1 GitHubからリポジトリをクローンする
```
$git clone https://github.com/515629/robosys2023.git
```
2 リポジトリのディレクトリに移動する
```
$cd robosys2023
```
## 使い方
次のコードを入力して実行する
```
$seq n | ./plus
```
ここで、nは任意の正の整数で、このコマンドは、1からnまでの整数の和を計算する
## 必要なソフトウェア
* Python
  * テスト済み: 3.7〜3.10

## テスト環境
* Ubuntu 22.04.2 LTS

## ライセンスや著作権
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可される
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものである
      * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2023 Jun Tokoeda
