
==========================================
乗りログアプリ
==========================================

目的
=====

Webブラウザーでコメントを登録するWebアプリケーションの練習。

ツールのバージョン
==================
:Python:    3.6.4
:Pip:       10.0.1

インストールと起動方法
==========================================

リポジトリーからコードを取得し、その下にvenv環境を用意します。::

    $ git clone https://github.com/beproud/norilog
    $ cd norilog
    $ python3.6 -m venv venv
    $ source venv/bin/activate
    (venv) $ pip install .
    (venv) $ norilog
    * Running no http://127.0.0.1:8000/

開発手順
========

開発用インストール
-------------------------------

1. チェックアウトする
2. 以下の手順でインストールする::

    (venv) $ pip install -e .

依存ライブラリ変更時
---------------------

1. ''setup.py''　の ''install_requires'' を更新する
2. 以下の手順で環境を構築する::

    (venv) $ deacitvate
    $ python3.6 -m venv --clear venv
    $ source venv/bin/activate
    (venv) $ pip install -e ./norilog

3. setup.pyをリポジトリーにコミットする