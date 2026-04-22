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
マージは「取り込み先のブランチで」実行する。
まず main に切り替え、最新化してから
feature ブランチをマージする。

git checkout main
git pull origin main
git merge feature/branch-practice

コンフリクトが発生した場合は内容を修正し、
git add → git commit でマージを完了する。
```

branch-practiceからの追加テキスト