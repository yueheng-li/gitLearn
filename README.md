# gitLearn
git 学习用repository，git操作，遇到的问题点。


## git在线学习
http://learngitbranching.js.org/

```
リポジトリの作成
git init

リポジトリのチェックアウト
git clone /path/to/repository
git clone username@host:/path/to/repository

アッド & コミット
git add <filename>
git add *
git commit -m "Commit message"

変更のプッシュ
git push origin master
git remote add origin <server>

ブランチ
作成
git branch XXX

切り替え
git checkout -b feature_x
git checkout master
git branch -d feature_x
git push origin <branch>

アップデート & マージ
git pull
git merge <branch>
git add <filename>

マージする前に差分を見る事もできます。
git diff <source_branch> <target_branch>

変更の取り消し
git checkout -- <filename>
git fetch origin
git reset --hard origin/master

```
