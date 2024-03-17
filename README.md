## githubで使用したコマンドのメモ

### commit済のファイルorフォルダをgitignoreでgit管理対象から外す
①リモートリポジトリにcommit済のファイルorフォルダを削除
```sh
git rm --cached [filepath]
git rm --cached -r [folderpath]
```
②gitignoreに除外したいファイルやフォルダのパスを記述しコミット
