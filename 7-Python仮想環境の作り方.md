# Python仮想環境の作り方

## 1. WSLを起動

<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;"><span class="Unicode">⊞</span> Win</kbd>
+
<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">S</kbd>で検索を起動し、「ubuntu」を検索し、「Ubuntu」をクリックしてWSLを起動する

## 2. 「プロンプト」とは
「プロンプト」とは、コンピュータ関連では主に2つの意味がある。

一つは、文字を打ってコンピュータに指示をする、コマンド・ライン・インタフェース(CLI)で、現在入力が可能な状態であることを示す「$ 」「% 」「C:￥Users¥ower> 」などである。
「入力促進記号」とも言われる。

もう一つは、生成AIに対する文字での「指示」のことである。

## 3. 「プロンプト」の確認

「入力促進記号」の方のプロンプトを確認する。
プロンプトに「(仮想環境名) user@example $」のように書かれていれば、既に仮想環境に入っている。
プロンプトが「user@example $」のようになっている場合は、仮想環境に入っていない。

## 4. 仮想環境がなければ作る

```sh
python3 -m pip install --upgrade pip
python3 -m venv 仮想環境名
```

# 5. 仮想環境に入る

```sh
source 仮想環境名/bin/activate
```

# 6. プロンプトを確認

プロンプトが「(仮想環境名) user@example %」のようになれば、仮想環境に入った。

# 7. 仮想環境を抜ける
```sh
deactivate
```
