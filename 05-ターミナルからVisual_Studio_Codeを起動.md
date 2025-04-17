# ターミナルからVisual Studio Codeを起動

## ~/.zshrcを作る
```sh
touch ~/.zshrc
```

## ~/.zshrcをVisual Studio Codeで開く
```sh
open -a /Applications/Visual\ Studio\ Code.app ~/.zshrc
```

## ~/.zshrcの末尾に以下を追加して保存する
```
alias code='open -a /Applications/Visual\ Studio\ Code.app'
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
