# サーバレッスン
Linuxプラクティス
-----------------
- ls : 配下のファイル、ディレクトリを表示する  
- pwd : ワーキングディレクトリのパスを表示する  
- cd : ワーキングディレクトリを変更する  
- mkdir : ディレクトリを作成する  
	- mkdir -p : 存在しない途中のディレクトリも含めて作成する  
- touch : ファイルを作成する  
- cp : ファイルをコピーする  
	- cp -r : ディレクトリをコピーする  
- mv A B : Bが存在するディレクトリの場合、AをBに移動する。存在しない場合、Aの名前をBに変更する  
- rm : ファイルを削除する  
	- rm -r : ディレクトリを削除する  
	- rm -f : 警告なしで削除する  
- echo : 表示する  
	- echo sentence > file : fileにsentenceを書き込む。fileが存在する場合、上書きし、存在しない場合、ファイルを作成の上で書き込む  
	- echo sentence >> file : fileが存在しない場合、>と同じ。既存の場合、末尾に書き込む  
- cat : ファイルの内容をターミナル上に出力する  
- vi : エディタを開く
