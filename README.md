 # 初期設定

- gitの情報をユーザ情報を連絡
- hugoインストール    
  - https://gohugo.io/getting-started/installing/  
- gitインストール    
  - https://qiita.com/godgarden/items/28bc299b35c5c60a5877  
- gitでclone     
  - コマンドで$ git clone git@github.com:kuniatsu/kuraseru.git


# hugoを0から動かすためのCommand
hugo new site {Project名}  
cd themes  
git submodule add  {対象GitURL}/*https://github.com/danielkvist/hugo-terrassa-theme*/  
cd ..  
echo theme = \"hugo-terrassa-theme\" >> config.toml   
hugo server  
  

# 記事作成
- コマンドで$ hugo new posts/{{日付}}.mdを実行    
- 作成されたcontent/posts/{{日付}}.mdを編集する    
  - title: にタイトルを書く    
  - draft: true をコメントアウトする    
  - 更新内容を書く     
- コマンドで$ hugoをコマンドする    
- gitでcommitしpushする    
- https://kuniatsu.github.io/kuraseru/  にアクセスして動作確認    


# TOPのimageを変更
> /hugo/kuraseru/docs/images
に画像追加

> /hugo/kuraseru/content/_index.md
の画像名を変更

> $ hugo
をコマンド




----------------------




