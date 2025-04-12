# WSLを起動

<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;"><span class="Unicode">⊞</span> Win</kbd>
+
<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">S</kbd>で検索を起動し、「ubuntu」を検索し、「Ubuntu」をクリックしてWSLを起動する

# Ollamaのインストール

WSLで以下のように打ってインストールする

```sh
curl -fsSL https://ollama.com/install.sh \| sh
```

# OllamaでLLMをダウンロード

とりあえず小さいLLaMa 3.2をダウンロード

```sh
ollama pull llama3.2
```

# OllamaでLLMを起動
```sh
ollama run llama3.2
```

起動したら、何か質問して応答を確認する

終了は
```sh
/bye
```

# OllamaにインストールされたLLMの一覧
```sh
ollama list
```

# Open WebUIのインストール
```sh
cd
mkdir open-webui
cd open-webui
python3 -m venv 仮想環境名(例えばopen-webui)
python3 -m pip install --upgrade pip
source 仮想環境名/bin/activate
python3 -m pip install open-webui
```

# Open WebUIの起動
```sh
python3 -m open-webui serve
```

終了するには<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">Ctrl</kbd>
+
<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">C</kbd>

# Open WebUIへのアクセス

ブラウザで以下にアクセス
```
http://localhost:8080/
```
