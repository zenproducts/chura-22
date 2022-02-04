# 【初心者向け】Pythonで手軽に始める文章校正

**簡単な算数でできる文章校正。**

こちらのイベントで発表した際のJupyterNotebookです。

https://churadata.connpass.com/event/234308/

## ノートブック

* [簡単に形態素解析したり、N-gramで遊ぶデモ](./demo_nl.ipynb)
* [Pythonと単純な辞書と集合だけで文章校正を作る](./synonym_simple.ipynb)

## 環境構築

```bash
$ sudo apt install mecab libmecab-dev
$ pip install fugashi unidic-lite
```

## テキストデータの準備

このディレクトリー以下に、 `corpus.txt` というファイル名で学習するためのテキストを配置します。
1行ごとに日本語の1文（1センテンス）が含まれたファイルにしてください。
