# 一个使用vue3写的扫雷小游戏

## 小巧 轻快 点击即玩
- 扫雷 ：[在线地址](https://jinhuid.github.io/Minesweeper/)

## 获得源码
> 下载index.html 或点击一键复制

## 实现功能
+ 支持自定义难度
+ 缓存关卡配置
+ 防止首次点击爆炸
+ 标旗子
+ 游戏计时
+ 游戏通过或失败判断等

## 最后
> 一开始只是想写着玩玩的 所以就一个html文件就完事了 但是看到别人的扫雷支持100 * 100的规模游戏 我发现我的上这个规模有些？卡卡的？那必不服输啊 所以在原本的基础上继续改了。这个游戏 我使用vue3来完成的 本来是想快点看到效果的 过程中 我才发现reactive的读取性能不是那么好 而这个游戏那就是大量的访问属性 给我整不会了 最后改成了 先操作原始数据 然后手动触发依赖来更新视图 性能还是不错滴 但是dom嘛 毕竟还是dom 跟canvas比不了 需要渲染大量的dom 不过这样也是没办法了 。最后100 * 100的规模话的还是能玩的 优化不了了 水平不够。原本是想快速开发的 最后我的感受是找罪受 。。。
