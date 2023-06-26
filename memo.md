# git initで初期化
$ git init
ローカルのリポジトリが作成されます
何か変更を加える

# commit の前に、git addでステージに追加する
* git add 対象ファイル名
* git add 対象ディレクトリ名
* git add .
VScodeでステージする場合は、
右クリックしてstage change


# commit コミットの仕方
$ git commit -m "comment "

## error
[no changes added to commit]
* 最初にステージする
* 次にコミットする
* use "git add" and/or "git commit -a"

# push　pushの仕方
$  git push origin main

vscodeのターミナルで、
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
を入力する
