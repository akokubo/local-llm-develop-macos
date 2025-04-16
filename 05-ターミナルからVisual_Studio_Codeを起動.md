# ターミナルからVisual Studio Codeを起動

## ~/.zshrcをVisual Studio Codeで開く
```sh
open -a /Applications/Visual Studio Code.app ~/.zshrc
```

## ファイルの末尾に以下を追加する
```
alias code='open -a /Applications/Visual Studio\ Code.app'
```

## ~/.zshrcの変更を読み込む
```sh
source ~/.zshrc
```

## 確認
ターミナルで以下のように打つ
```sh
code
```
