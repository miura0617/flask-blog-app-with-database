# 実行方法

## VSCodeのターミナルとしてPowerShell起動

## 仮想環境の作成
python -m venv venv

## 仮想環境実行
venv\Scripts\activate

## Pythonパッケージインストール
pip install -r requirements.txt

## Python対話モードでSQLiteのDB(blog.db)を作成
python3 

\>\>\>\> from app import db 

\>\>\>\> db.create_all() 


## Flask環境変数設定
$env:FLASK_APP = "app"
$env:FLASK_ENV = "development"

## Flaskサーバ起動
flask run

## Flaskサーバへアクセス
http://127.0.0.1:5000/
