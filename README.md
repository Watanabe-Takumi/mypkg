# mypkg
これはロボットシステム学の第2課題です

機能
count.pyを実行するとカウントアップが開始しその後twice.pyを実行するとcount.pyによってカウントした数値の2倍の値が返されます。
(非同期なので数値の抜けあり)

使用機材：Raspberry Pi3 ModelB+
　　　　　Ubuntu 20.04 LTS
     
使用方法
1．PCからLTSを使用してRaspberry Pi3にログイン(この時2つWindowを開いてログインしておく)
2．Raspberry Pi3にROSをダウンロード
3. ROSを起動する
4．このリポジトリからcloneを作製
5．ファイルの中に入る
5．rosrun mypkg count.pyを実行(実行したWindowは閉じずに開いておく)※この時点ではWindowに何も表示されないが気にしない
6．もう一つのWindowからrosrun mypkg twice.pyを実行
