# Gitの設定

## Gitとは
Gitとは、分散バージョン管理システムの一つである。

「バージョン管理システム」とは、ファイルのバージョン管理を行うためのツールである。
任意の時点でのファイルの状態を保存し、過去の状態に戻したり、変更履歴を追跡したりすることができる。
Gitは、特にソースコードの管理に特化しており、プログラムの開発や保守に広く利用されている。

また、「分散」とは複数の人たちで共同で利用できることを意味する。
インターネットからプログラムを取得したり、プログラムを配布することができる。

## Gitの設定
WSLには既にGitがインストールされている。
そこで、ここではGitの設定を行う。

### WSLからVisual Studio Codeを起動

<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;"><span class="Unicode">⊞</span> Win</kbd>
+
<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">S</kbd>
で検索を起動し、「ubuntu」を検索し、「Ubuntu」をクリックしてWSLを起動する

### Gitのメールアドレスとユーザー名を設定
WSLで以下のように打つ。

```sh
git config --global user.email メールアドレス
git config --global user.name "名前"
```
