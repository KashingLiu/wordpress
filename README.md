# wordpress
哈工大（威海）校园学习助手

这不是最终版本，有些地方写的不是很完善：
1、每个功能的菜单项与其他页面的连接有问题，包括连接不到页面，当前选项没有变成灰色
2、在class中的提醒功能存在逻辑问题。

提醒功能的设计思路：
首先是Linux里的crontab提供了一个守护的功能，可以定时执行操作，我这里是写了一个php a.php的.sh文件，可以用crontab定时执行.sh文件。
一天有四次提醒，分别对应a.sh、b.sh、c.sh和d.sh
