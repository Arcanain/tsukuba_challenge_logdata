# tsukuba_challenge_logdata

rosbagを使用してdataの保存と再生を行う

# rosbag
以下のコマンドでpublishされているtopic情報を全て保存する

```bash
rosbag record -a
```

以下のコマンドで.bagファイルの再生を行う

```bash
rosbag play 生成したファイル名.bag
```
# cartographerによる地図生成
保存した.bagファイルを再生して地図生成を行うには以下のlaunchファイルを実行する

```bash
roslaunch cartgrapher_navigation cartographer_rosbag.launch 
```
