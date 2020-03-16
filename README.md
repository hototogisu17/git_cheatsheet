##### ユーザ名, アドレスの設定
`git config --global user.name ユーザ名`  
`git config --global user.email メールアドレス`

##### エイリアスの設定
`git config --global alias.co checkout`  
`git config --global alias.st status`  
`git config --global alias.ci commit`  
`git config --global alias.br branch`

##### editorの設定
`git config --global core.editor vim`  

##### ファイルの変更の取り消し
`git checkout -- ファイル名 or ディレクトリ名 or .`  

##### ステージングの取り消し
`git reset HEAD ファイル名 or ディレクトリ名 or .`  

##### ファイルの削除
`git rm ファイル名`  

##### フォルダの削除
`git rm -r フォルダ名`  

##### コミットの修正
`git commit --amend`  

##### ブランチの作成
`git branch ブランチ名`  

##### ブランチの移動
`git checkout ブランチ名`  

##### ブランチの削除
`git branch --delete ブランチ名`  
