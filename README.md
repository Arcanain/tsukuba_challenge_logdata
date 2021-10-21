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
