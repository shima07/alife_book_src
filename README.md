# 作って動かす ALife - 実装を通した人工生命モデル入門

---

![表紙](https://user-images.githubusercontent.com/1583412/43062946-5a31d5b8-8e95-11e8-802a-53d2e58dc93e.jpeg)

---

本リポジトリはオライリー・ジャパン発行書籍『[作って動かす ALife](https://www.oreilly.co.jp/books/9784873118475/)』のサポートサイトです。

## ファイル構成

|フォルダ名 |説明                         |
|:--        |:--                          |
|chap02       |2章で使用するソースコード    |
|chap03       |3章で使用するソースコード    |
|...        |...                          |
|chap06_07       |6,7章で使用するソースコード    |
|alifebook_lib   |各章で利用するユーティリティライブラリ  |


ソースコードの解説は本書をご覧ください。

## 必要条件
ソースコードの実行環境と必要なパッケージは以下です。

* Python 3.x
* NumPy
* Matplotlib

本書全体

* Python 3.6.3
* NumPy  1.14.5
* Vispy  0.5.3
* PyQt  5.10.1

5章
* Pyglet 1.3.2
* Pymunk  5.3.2

6章および7章

* Pillow  5.1.0
* Keras  2.2.0
* TensorFlow  1.8.0

※Pythonのバージョンは、3系を利用します。

## 推奨環境セットアップ方法

1. anacondaのインストール

https://www.anaconda.com/download/

2. 必要なライブラリのインストール

```terminal
$ pip install pyglet pymunk vispy keras Pillow
```


## 実行方法

各章のフォルダへ移動して実行してください。

```terminal
$ cd chap02
$ python game_of_life.py
```

詳しい実行方法は本書をご覧ください。

## ライセンス

本リポジトリのソースコードは[MITライセンス](http://www.opensource.org/licenses/MIT)です。
商用・非商用問わず、自由にご利用ください。


### 6,7章で利用するkerasのバックエンドについて

kerasがインストール済みで、バックエンドをtensorflow以外に設定している場合はエラーが出るので、tensorflowに切り替えてください.
https://keras.io/ja/backend/
