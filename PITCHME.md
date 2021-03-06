### Pyhtonの特徴と
### 注目ライブラリのご紹介

< OSS X Users Meeting > #19 Python

Takanori Suzuki / 2017-06-29
---

### Who am I?(お前誰よ)

* 鈴木たかのり / Takanori Suzuki
* Twitter: @takanory
* 株式会社ビープラウド
* 一般社団法人PyCon JP 理事
* Pythonボルダリング部(#kabepy)部長

---

### 今日話すこと

* Pythonとは
* Pythonの特徴
* 注目ライブラリ
* Pythonを学ぶには

---

### 最初に質問

* Python知ってる人?
* Python書いたことある人? |
* 他のプログラミング言語は知ってる人? |

---

### Pythonとは

---

### Pythonとは

* マルチプラットフォーム
* マルチパラダイム
* Python 3
* 豊富なライブラリ

---

### マルチプラットフォーム

* Windows
* macOS
* Linux
* 他

---

### マルチパラダイム

* オブジェクト指向
* 命令形
* 手続き型
* 関数型

---

### Python 3

* 今から使うならPython 3一択
* 最新バージョンは 3.6.1
* 日本語の文字コードに悩まされにくい

```python
print('こんにちは世界!') # Python 3系
print 'こんにちは世界!' # Python 2系
```

---

### 豊富なライブラリ

* 400弱の標準ライブラリ
* https://docs.python.jp/3/library/index.html

![標準ライブラリ](images/standard-library.png)

---

### 豊富なサードパーティ製パッケージ

* 多数のパッケージ
* https://pypi.python.org/pypi

![PyPI](images/pypi.png)

---

### Python の特徴

---

### Python の特徴

* 読みやすいコード
* PEP8: コーディングスタイル
* PEP: 拡張提案
* Pythonでできること

---

### 読みやすいコード

* 構造(ブロック)をインデントで表現

```python
for num in range(1,101):
    if num % 15 == 0:
        print('Fizz Buzz')
    elif num % 3 == 0:
        print('Fizz')
    elif num % 5 == 0:
        print('Buzz')
    else:
        print(num)
```

---

### PEP8: コーディングスタイル

* PEP 8: Style Guide for Python Code
* https://www.python.org/dev/peps/pep-0008/
  * OK: `spam(ham[1], {eggs: 2})`
  * NG: `spam( ham[ 1 ], { eggs: 2 } )`
  * OK: `dct['key'] = lst[index]`
  * NG: `dct ['key'] = lst [index]`

---

### PEP8: コーディングスタイル

* 各種サポートツール
  * pycodestyle: PEP8のチェック
  * autopep8: 自動的に書き換える
  * flake8: pycodestyle + 論理チェック

---

### PEP: Pythonの拡張提案

* Python Enhancement Proposal
* https://www.python.org/dev/peps/

![PEP](images/peps.png)

---

### Pythonでできること

* コマンドラインツール
* バッチ処理
* Web開発
* 機械学習
* 構成管理
* ドキュメンテーション
* その他いろいろ

---

### 注目ライブラリ

---

### 注目ライブラリ

* Pythonライブレリ厳選レシピ
* Awesome Python

  * Web開発
  * 機械学習
  * 構成管理
  * ドキュメンテーション
  * その他

---

### Pythonライブラリ厳選レシピ

* http://gihyo.jp/book/2015/978-4-7741-7707-6
* 「これだけは知っていてほしい」を厳選

  * 標準ライブラリ
  * サードパーティ製パッケージ

![Pythonライブラリ厳選レシピ](images/recipe.jpg)

---

### Awesome Python

* https://github.com/vinta/awesome-python

![Awesome Python](images/awesome-python.png)

---

### Web開発

* Webフレームワーク

  * Django: https://www.djangoproject.com/
  * Bottle: https://bottlepy.org/

* Webスクレイピングフレームワーク

  * Scrapy: https://scrapy.org/

---

### 機械学習

* NumPy, SciPy: 数値計算、科学計算
* Pandas: データ解析
* scikit-learn: 機械学習
* Matplotlib, Bokeh: 可視化
* Keras, Caffe, TensorFlow: ディープラーニング
* NLTK: 自然言語処理
* 詳細は次のセッションで

---

### 構成管理

* Ansible: https://www.ansible.com/
  * YAMLで記述

![Ansible](images/ansible.png)

---

### ドキュメンテーション

* Sphinx: http://www.sphinx-doc.org/
  * reStructuredText または Markdown で記述

![Sphinx](images/sphinx.png)

### その他

* OpenPyXL: https://openpyxl.readthedocs.io/
  * Excelファイルの読み書き
* Slackbot: https://github.com/lins05/slackbot
  * Slack(チャット)のbotフレームワーク
* awscli: https://aws.amazon.com/jp/cli/
  * AWSのコマンドラインツール
---

### Pythonを学ぶには

---