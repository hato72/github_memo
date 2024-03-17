## githubで使用したコマンドのメモ

### リモートリポジトリにコミット済のファイルorフォルダをgitignoreでgit管理対象から外す
①リモートリポジトリにコミット済のファイルorフォルダをリモートリポジトリから削除
```sh
git rm --cached [filepath]
```
または
```sh
git rm --cached -r [folderpath]
```
②gitignoreに除外したいファイルやフォルダのパスを記述しコミット
