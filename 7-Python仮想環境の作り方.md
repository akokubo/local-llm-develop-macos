# WSLを起動

<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;"><span class="Unicode">⊞</span> Win</kbd>
+
<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">S</kbd>で検索を起動し、「ubuntu」を検索し、「Ubuntu」をクリックして起動する

# プロンプトを確認

プロンプトに「(仮想環境名)」のように書かれていれば、既に仮想環境に入っている

# 仮想環境がなければ作り、アップデートする

```sh
python3 -m venv 仮想環境名
python3 -m pip install --upgrade pip
```

# そのフォルダにある仮想環境に入る

```sh
source 仮想環境名/bin/activate
```

# プロンプトを確認

プロンプトに「(仮想環境名)」のように書かれていれば、仮想環境に入った
