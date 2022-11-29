# RoboSys2022_commandpack
![test](https://github.com/Cola0912/Robosys/actions/workflows/test.yml/badge.svg)

提出用

講義の中で作ったものを筆頭に思いついたコマンドを追加していく。

### 使う準備
```bash
  git clone https://github.com/Cola0912/RoboSys2022.git
  cd RoboSys2022
```

# plusコマンド

標準入力から読み込んだ数字を足すことができるコマンド。

* 使用例
```bash
  seq 10 | ./plus
```
* 出力結果
  55

### 必要なソフトウェア
* Python
  * テスト済み: 3.7 ~ 3.10


# pokedexコマンド
  ポケモンの名前もしくは図鑑番号の指定で、当該ポケモンの情報を表示します。

* 使用例
```bash
  ./pokedex 25
```
* 出力結果
  No. 25
  name:    pikachu
  types:   electric

### 必要なソフトウェア
* Python
  * テスト済み: 3.7 ~ 3.10


## Open API

<img src="https://user-images.githubusercontent.com/24237865/83422649-d1b1d980-a464-11ea-8c91-a24fdf89cd6b.png" align="right" width="21%"/>

[PokeAPI](https://pokeapi.co/)を使用しています。


## テスト環境
* Ubuntu20 及びWSL内 Ubuntu20 のPython3.7 ~ 3.10

## ライセンス
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布及び使用が許可されます。

©︎ 2022 Shusei Aida
