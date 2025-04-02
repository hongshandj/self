本项目是用LabVIEW设计的一个扫雷游戏。

本人自用用于课程的报告。

参考b站的一个up主原视频如下
【LabVIEW扫雷】 https://www.bilibili.com/video/BV1Pi4y1w7GB/?share_source=copy_web&vd_source=0a9eba5bd01e399192db1aa11bd6a879

本人修改了如下BUG：
如果只剩最后两个格子，一个是雷，另一个不是，那么随便点一个都会显示胜利，因为判断胜利的条件是剩余的方块是否小于等于雷数。我加入了一个是否踩雷的全局变量，多一个判断条件得以解决。

更新了实时显示时间。