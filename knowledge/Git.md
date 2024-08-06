### 親ブランチの変更を子ブランチに取り込む
親ブランチに移動する
```bash
git checkout 親ブランチ名
```

親ブランチの状態を取り込む
```bash
git pull 親ブランチ名
```

子ブランチに移動する
```bash
git checkout 子ブランチ名
```

子ブランチに親ブランチの状態を取り込む
```bash
git merge 親ブランチ名
```
※rebaseでもできるらしい
