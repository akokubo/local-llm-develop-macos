# Python環境の構築
## 1. WSLを起動

<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;"><span class="Unicode">⊞</span> Win</kbd>
+
<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">S</kbd>で検索を起動し、「ubuntu」を検索し、「Ubuntu」をクリックしてWSLを起動する

## 2. Pythonライブラリを管理するpipを入れる
WSLで以下のように打つ

```sh
sudo apt install python3-pip
```

## 3. Pythonのバージョンを調べる

```sh
python3 --version
```

## Python仮想環境を作るvenvを入れる
```sh
sudo apt install python3.12-venv
```

※上で調べたPythonのバージョンに合わせる
