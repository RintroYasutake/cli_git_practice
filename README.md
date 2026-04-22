# cli_git_practice

2026/4/24

GITのCLI(コマンドライン)でのクローン
```
git clone git@github.com:RintroYasutake/cli_git_practice
```

ステージング & コミット
```
git add .\README.md
git commit -m "first commit"
```

ブランチ
```
確認：git branch
新規：git checkout -b feature/branch-practice
移動：
git checkout main
git checkout feature/branch-practice
```

中段はジャスパしろ

キャミィのワンボタンSA3は強い

ザンギはSA3がたまったら別キャラになる

マージ
```
git checkout main
git merge feature/branch-practice
```