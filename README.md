<div id="top"></div>

## 使用技術一覧

<p style="display: inline">
  <!-- バックエンドのフレームワーク一覧 -->
  <img src="https://img.shields.io/badge/-Django-092E20.svg?logo=django&style=for-the-badge">
  <!-- バックエンドの言語一覧 -->
  <img src="https://img.shields.io/badge/-Python-F2C63C.svg?logo=python&style=for-the-badge">

<!-- プロジェクト名を記載 -->
  
## プロジェクト名

花の名前を教えてくれるwebアプリ

<!-- プロジェクトについて -->

## プロジェクトについて

## ディレクトリ構成

<!-- Treeコマンドを使ってディレクトリ構成を記載 -->

❯ tree -a -I "node_modules|.next|.git|.pytest_cache|static" -L 2

│  db.sqlite3
│  manage.py
│
├─flower
│  │  admin.py
│  │  apps.py
│  │  forms.py
│  │  models.py
│  │  tests.py
│  │  urls.py
│  │  views.py
│  │  __init__.py
│  │
│  ├─migrations
│  │  │  0001_initial.py
│  │  │  __init__.py
│  │  │
│  │  └─__pycache__
│  │          0001_initial.cpython-310.pyc
│  │          __init__.cpython-310.pyc
│  │
│  ├─recognition
│  │  │  model.py
│  │  │  recognize.py
│  │  │  train.py
│  │  │
│  │  ├─data
│  │  │  │  data.py
│  │  │  │  label.txt
│  │  │  │  setup.py
│  │  │  │
│  │  │  └─__pycache__
│  │  │          data.cpython-310.pyc
│  │  │
│  │  ├─save_model
│  │  │      model_10.pth
│  │  │      model_15.pth
│  │  │      model_20.pth
│  │  │      model_5.pth
│  │  │
│  │  └─__pycache__
│  │          model.cpython-310.pyc
│  │          recognize.cpython-310.pyc
│  │
│  ├─templates
│  │  └─flower
│  │          result.html
│  │          showall.html
│  │          upload.html
│  │
│  └─__pycache__
│          admin.cpython-310.pyc
│          apps.cpython-310.pyc
│          forms.cpython-310.pyc
│          models.cpython-310.pyc
│          urls.cpython-310.pyc
│          views.cpython-310.pyc
│          __init__.cpython-310.pyc
│
├─media
│  └─images
│          large.jpg
│          large_Ixk2Xit.jpg
│
└─mysite
    │  asgi.py
    │  settings.py
    │  urls.py
    │  wsgi.py
    │  __init__.py
    │
    └─__pycache__
            settings.cpython-310.pyc
            urls.cpython-310.pyc
            wsgi.cpython-310.pyc
            __init__.cpython-310.pyc

### アプリの起動と動作確認

以下のコマンドでwebアプリを起動

python manage.py runserver

### 動作確認

[http://127.0.0.1:8000 ](http://127.0.0.1:8000/flower/upload)にアクセスできるか確認
アクセスできたら成功
