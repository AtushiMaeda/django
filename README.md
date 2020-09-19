# django

簡易SNSを作った。

## python3のインストール
Homebrewがインストール済みであること

pyenvをインストールする
```
brew install pyenv
```
インストール終わったら

```
pyenv -v
```

'pyenv 1.1.0'が表示されればOK

```
pyenv install --list
```
でインストール可能なバージョンを表示

今回はPython3.8.0をインストール

```
pyenv global 3.8.0
```

インストール終わったら

```
python --version
```
でバージョンが表示されればOK！


## pip install

```
pip install django
```

でDjangoのインストール。

## Serverの起動
boardprojectディレクトリに移動して下記コマンドを実行する

```
python3 manage.py runserver
```
