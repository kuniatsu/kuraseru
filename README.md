 # 初期設定

・hugoインストール    
・gitインストール    
・gitでclone     




# 記事作成
・コマンドで$ hugo new posts/{{日付}}.mdを実行    
・作成されたcontent/posts/{{日付}}.mdを編集する    
ー・title: にタイトルを書く    
ー・draft: true をコメントアウトする    
ー・更新内容を書く     
・コマンドで$ hugoをコマンドする    
・gitでcommitしpushする    
・https://kuniatsu.github.io/kuraseru/  にアクセスして動作確認    






# hugoをローカルで動かすためのCommand

hugo new site {Project名}  
cd themes  
git submodule add  {対象GitURL}/*https://github.com/danielkvist/hugo-terrassa-theme*/  
cd ..  
echo theme = \"hugo-terrassa-theme\" >> config.toml   
hugo server  
  
  




