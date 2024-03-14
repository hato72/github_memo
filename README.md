### githubで使用したコマンドのメモ

#### commit済のファイルorフォルダをgitignoreでgit管理対象から外す
リモートリポジトリにcommit済のファイルorフォルダを削除
```sh
git rm --cached $[filepath]
git rm --cached -r $[folderpath]
```
gitignoreに除外したいファイルやフォルダを記述
