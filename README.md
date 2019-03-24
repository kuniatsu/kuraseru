 # 初期設定

・hugoインストール    
・gitインストール    
・gitでclone     




# 記事作成
1. コマンドで$ hugo new posts/{{日付}}.mdを実行    
2. 作成されたcontent/posts/{{日付}}.mdを編集する    
  * title: にタイトルを書く    
  * draft: true をコメントアウトする    
  * 更新内容を書く     
3. コマンドで$ hugoをコマンドする    
4. gitでcommitしpushする    
5. https://kuniatsu.github.io/kuraseru/  にアクセスして動作確認    






# hugoをローカルで動かすためのCommand

hugo new site {Project名}  
cd themes  
git submodule add  {対象GitURL}/*https://github.com/danielkvist/hugo-terrassa-theme*/  
cd ..  
echo theme = \"hugo-terrassa-theme\" >> config.toml   
hugo server  
  
  




