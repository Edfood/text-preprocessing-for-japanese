# text-preprocessing-for-japanese
日本語テキストの前処理(文字等の正規化、トークナイズ)を行うためのipynbファイルです。

## セットアップ

```shell script
$ brew install mecab
$ brew install mecab-ipadic
$ git clone https://github.com/neologd/mecab-ipadic-neologd.git
$ ./mecab-ipadic-neologd/bin/install-mecab-ipadic-neologd -h
$ pip install pipenv
$ pipenv install
$ git clone https://github.com/Edfood/text-preprocessing-for-japanese
$ cd text-preprocessing-for-japanese
```

## 使い方

1. dataフォルダの中に、前処理を行うテキストファイルを`raw.txt`というファイル名で配置

2. 以下のコマンドを実行

```shell script
$ pipenv shell
$ jupyter notebook
```

3. ノートブックが立ち上がったら、上から順に全てのセルを実行
