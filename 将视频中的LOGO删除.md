将视频中的LOGO删除

delogo

X:Y:W:H

位置，宽高

show = 1 坐标 绿框

```
ffplay -i video_w.mp4 -vf "delogo=640-64-30:10:64:60:show=1"
```

```
ffmpeg -i video_w.mp4 -vf "delogo=640-64-30:10:64:60:show=1" video_d.mp4
```

