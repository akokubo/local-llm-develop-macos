# Ollamaのインストール

以下のDownloadからmacOS版をダウンロードし、ダブルクリックしてインストールする。

https://ollama.com/

# OllamaでLLMをダウンロード

ターみなるで、とりあえず小さいLLaMa 3.2をダウンロード

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
conda activate py3129
pip install open-webui
```

# Open WebUIの起動
```sh
open-webui serve
```

# Open WebUIへのアクセス

ブラウザで以下にアクセス
```
http://localhost:8080/
```

# Open WebUIの終了
終了するには<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">Ctrl</kbd>
+
<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">C</kbd>
