# 2-WSLのインストールと設定

参考

https://learn.microsoft.com/ja-jp/windows/wsl/install

https://learn.microsoft.com/ja-jp/windows/wsl/basic-commands

# 拡張子を表示させる設定を行う

# WSLの最新版をダウンロード

以下にアクセスして

https://github.com/microsoft/WSL/releases

Latest(最新)バージョンの .msi をCPUに合わせてダウンロード

Intelはx64

AMDはarm64

# WSLの最新版をインストール

ダウンロードした .msi をダブルクリックしてインストール

インストールが終わったら、Windowsを再起動

# WSLのユーザー設定

<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;"><span class="Unicode">⊞</span> Win</kbd>
+
<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">S</kbd>
で検索を起動し、「WSL」を検索し、クリックして起動する

ユーザー名とパスワードを設定するように言われる

これはWindowsとは独立である(同じにしてもいい)

なお、パスワードは打っても見えない。以降も同様。

# WSLをアップデート

<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;"><span class="Unicode">⊞</span> Win</kbd>
+
<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">S</kbd>で検索を起動し、「PowerShell」を検索し、「Windows PowerShell」の「管理者として実行する」をクリックして起動する

Windows PowerShellで以下のように打つ。

```sh
wsl --update
```

<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;"><span class="Unicode">⊞</span> Win</kbd>
+
<kbd class="keyboard-key nowrap" lang="en" style="border: 1px solid #aaa; border-radius: 2px; box-shadow: 1px 2px 2px #ddd; background-color: #f9f9f9; background-image: linear-gradient(top, #eee, #f9f9f9, #eee); padding: 1px 3px; font-family: inherit; font-size: 0.85em;">S</kbd>で検索を起動し、「ubuntu」を検索し、「Ubuntu」をクリックしてWSLを起動する

WSLで以下のように打つ。

```sh
sudo apt update
sudo apt upgrade
```

パスワードを聞かれたら打つ(見えない)。以降も同様。

Y/nと聞かれたら「y」
