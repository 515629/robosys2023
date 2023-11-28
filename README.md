# robosys2023
# plusコマンド
[![test](https://github.com/515629/robosys2023/actions/workflows/test.yml/badge.svg)](https://github.com/515629/robosys2023/actions/workflows/test.yml)

## 何をするためのソフトウェアか
このソフトウェアは,標準入力から読み込んだ数字を足すものです。

## インストール方法
1 plusファイルをダウンロードします。以下のコマンドを実行してダウンロードできます：
wget https://github.com/515629/robosys2023/raw/main/plus

2ダウンロードしたplusファイルを実行可能にします：

```chmod +x plus

## 使い方
1ターミナルを開き、plusコマンドを実行します：
./plus

2標準入力から数字を入力します。複数の数字を入力する場合は、改行で区切ります。例えば、5と15を足し合わせる場合は以下のように入力します：
5
15

3入力が完了したら、Ctrl+Dを押します。すると、入力した数字の合計が出力されます。

## 必要なソフトウェア
* Python
  * テスト済み: 3.7〜3.10

## テスト環境
* Ubuntu

* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
  * © 2023 Jun Tokoed
