## openbrows.pyの使い方。

## このレポジトリをダウンロードする。
青いCodeボタンから、Download zipを押してダウンロードする。

## 展開する
zipを任意の場所に置いて展開する。
```
ex)
C:/User/python/openbrows.zipに展開
C:/User/python/openbrowsディレクトリができる。
```

## 仮想環境の実行
コマンドプロンプトから、仮想環境を動かす。
```
ex)
> C:/User/python/openbrows/Scripts/activate.bat <enter>
(opnebrowsenv) > # 仮想環境の実行に成功すると、左記のように（仮想環境名）> という表示になる。
```

## pythonファイルの実行
pythonは、ダウンロードしたファイル内にあるpythonを使う。
ファイルはフルパスで指定すること。
```
(opnebrowsenv) > C:/User/python/openbrows/Scripts/python.exe C:/User/python/openbrows/Scripts/openbrows.py
```
ブラウザが起動し、10s毎にブラウザが更新されれば成功。

## 注意
openbrows.py内のプログラム9行目のクロムドライバーのパスは、環境に合わせて変更すること。
```
driver_path = "C:/Users/mokos/AppData/Local/SeleniumBasic/chromedriver.exe" # あなたの環境に合わせてパスを修正してください
```
