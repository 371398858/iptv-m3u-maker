# IPTV 直播源 收集&汇总项目

#### 简介
---
主要功能是收集现有大佬发布的直播源m3u8文件

测试是否好用,并记录该源的访问延迟. 同时按一定规则格式化该源的标题.

最后程序会在同类的源中选出延迟最低的一个,按频道优先级汇总,并输出一个m3u文件.

**!!!这个项目的代码还在进行中!!!**

#### 使用方法
---
项目根目录执行
```
python main.py
```
即可

建议以docker的方式,直接在路由器上运行,本地检测地址访问,更为精准.


#### 目前资料来源
---
- https://www.jianshu.com/p/2499255c7e79
- https://github.com/billy21/Tvlist-awesome-m3u-m3u8
- V2ex - [Dotpy](https://www.v2ex.com/member/Dotpy) 提供1600+可用播放源

#### 运行环境
---
python3.7
