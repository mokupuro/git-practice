# git Cheat Sheet

## <a id="index" href="#index">目次</a>
* [リポジトリの作成](#section1)
* [変更の作成](#section2)
* [変更の整理](#section3)
* [変更の同期](#section4)
* [ファイル名の整理](#section5)
* [コミットの修正](#section6)
* [履歴の確認](#section7)

- - -

## <a id="section1" href="#section1">リポジトリの作成</a>

- リポジトリを新規作成するもしくは既存のURLから取得します
  
|git init [project-name]|
|:--|
|[project-name]のローカルリポジトリを作成します|
|git clone [url]|
|プロジェクトとすべてのバージョン履歴をダウンロードします|



## <a id="section2" href="#section2">変更の作成</a>
  
- 変更をレビューしコミット操作ログを作成します
   
|git status|
|:--|
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




## <a id="section3" href="#section3">変更の整理</a>

- 1連のコミットに名前をつけ、完了した成果を結合します
 
|git branch|
|:--|
|現在のリポジトリ上のすべてのローカルブランチを一覧で表示します|
|git branch [branch-name]|
|新規ブランチを作成します|
|git branch -d [branch-name]|
|指定されたブランチを削除します|
|git checkout [branch-name]|
|指定されたブランチに切り替え、作業ディレクトリを更新します|
|git merge [branch]|
|指定されたブランチを削除します|



## <a id="section4" href="#section4">変更の同期</a>

- リポジトリのブックマークを登録し、バージョン履歴を交換します


|git fetch [bookmark]|
|:--|
|リポジトリブックマークからすべての履歴をダウンロードします|
|git merge [bookmark]/[branch]|
|ブックマークのブランチを現在のローカルブランチに統合します|
| git push [alias] [branch]|
|すべてのローカルブランチのコミットをGitHubにアップロードします|
|git pull|
|ブックマークの履歴をダウンロードし、変更を統合します|



## <a id="section5" href="#section5">ファイル名の整理</a>

- バージョン管理されているファイルの移動、または削除を行ないます

|git rm [file]|
|:--|
|作業ディレクトリからファイルを削除し、削除をステージします|
|git rm --cached [file]|
|バージョン管理からファイルを削除して、ローカルのファイルは保持します|
|git mv [file-original] [file-renamed]|
|ファイル名を変更し、コミットします|




## <a id="section6" href="#section6">コミットの修正</a>

- ミスの削除と履歴の置き換え

|git reset [commit]|
|:--|
|[commit] 以降すべてのコミットを取り消し、ローカルでは変更を保持します|
|git reset --hard [commit]|
|指定されたコミットに戻り、それ以降のすべての変更を破棄します|



## <a id="section7" href="#section7">履歴の確認</a>

- プロジェクトファイルの進展を確認します

|git log|
|:--|
|現在のブランチのバージョン履歴を一覧で表示します|
|git log --follow [file]|
|名前の変更を含む指定したファイルのバージョン履歴の一覧を表示します|
|git diff [first-branch]...[second-branch]|
|２つのブランチ間の差分を表示します|
|git show [commit]|
|指定されたコミットのメタ情報と変更内容を出力します|


