根据新版本代码进行修改

仍存在的问题&bug：

- 涂鸦的图已经贴上去了，但游戏过程中碰到踏板会还会向下几个单位才进行反弹操作，初步判断是碰撞点 or 贴图后坐标的设定出了问题。
- 踏板的形状还是没有改成镇哥喜欢的椭圆形qaq，大家有什么方案就尽量改吧，目前绘制踏板所采用的是位于game.py 中 52 行的 blit函数（人太蠢了呜呜）
- 很多被注释掉的代码没有被清理掉（万一要用回来debug呢），注释也没有写完，需要补全，注释代码在交最终版之前删掉就好

暂时就发现这么多问题，代码应该拆的够开了方便缝合。

--by Mark Peng
