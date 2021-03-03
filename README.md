# git-practice
git/GitHubの練習用

## git Cheat Sheet

- リポジトリの作成
　　リポジトリを新規作成するもしくは既存のURLから取得します
  
|header1|
|:--|--:|:--:|
|git init [project-name]|
|[project-name]のローカルリポジトリを作成します|
|git clone [url]|
|プロジェクトとすべてのバージョン履歴をダウンロードします|

- 変更の作成
   変更をレビューしコミット操作ログを作成します
   
|git status|
|コミット可能なすべての新規または変更のあるファイルを一覧で表示します|
|git clone [url]|
|プロジェクトとすべてのバージョン履歴をダウンロードします|
|git add [file]|
|バージョン管理のためにファイルのスナップショットを作成します|
|git reset [file]|
|ファイルをステージングから外しますが、その内容は保持します|
|git diff|
|まだステージされていないファイルの差分を表示します|
|git commit -m "[commit message]"|
|ファイルのスナップショットをバージョン履歴内に恒久的に記録します|
