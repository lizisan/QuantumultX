# 以下是历史更新记录

## 2021/5/9 变动如下

* 增加网易云音乐策略与TikTok规则

* 在注释中添加[sngxpro](https://github.com/sngxpro)与[zwf234](https://github.com/zwf234)的task订阅地址

## 2021/5/8 变动如下

* 换用[ACL4SSR](https://github.com/ACL4SSR)的规则试试

## 2021/5/7 变动如下

* 精简配置，去除自己用不到的策略配置

* 重新试用[blackmatrix7](https://github.com/blackmatrix7)的聚合规则

## 2021/5/5 变动如下

* 增加Toonme重写规则

## 2021/4/25 变动如下

* 增加Guard策略组（感谢[Koolson](https://github.com/Koolson)的图标），方便在获取cookie时暂时停用去广告filter

## 2021/4/17 变动如下

* 跟随[神机](https://github.com/DivineEngine)在general下增添规则

## 2021/4/15 变动如下

* 修改资源解析器地址

* 精简配置

## 2021/4/11 变动如下

* 经过思考，决定放弃[blackmatrix7](https://github.com/blackmatrix7)的聚合规则，误杀现象比较严重，暂时还是不考虑了

* 增加“其余节点”策略，用于汇总其他策略筛选后的

* 更新crack与advertising重写规则，去除配置中[zwf234](https://github.com/zwf234)的rewrite规则

* 跟随[Orz-3](https://github.com/Orz-3)将解析器地址修改为CDN地址，分流地址修改为[神机](https://github.com/DivineEngine)Surge分流文件

## 2021/4/10 变动如下

* 增加Quantumult X 教程

* 修正geo_location_checker内部分国家/地区国旗代码错误

* 将addendum重写补充规则拆分

## 2021/4/9 变动如下

* geo_location_checker忘改了，改一下

* 把[sngxpro](https://github.com/sngxpro)的解锁vip规则加回来，但默认关闭

* 增添补充rewrite配置文件

## 2021/4/8 变动如下

* 去除TikTok重写规则，经常失效，有需要的请自行手动添加

* 将[DivineEngine](https://github.com/DivineEngine)的filter规则全部修改为[blackmatrix7](https://github.com/blackmatrix7)的聚合规则

* 将geo_location_checker替换为自己写的脚本（修改自[KOP-XIAO](https://github.com/KOP-XIAO)）

* 上传了两个机场icon

## 2021/4/7 变动如下

* 调整部分规则排列顺序，使之更顺眼

* 增加Task作者订阅地址

* rewrite和部分filter换回[blackmatrix7](https://github.com/blackmatrix7)规则

## 2021/4/6 变动如下

* 精简配置，去除一些不常用的功能

* 暂时去除rewrite模块中[sngxpro](https://github.com/sngxpro)的unlockvip订阅（不知道为什么会与今日头条冲突，导致今日头条无法刷新，zwf234的已经能覆盖大部分，盲猜不影响使用体验）

* 将[blackmatrix7](https://github.com/blackmatrix7)的rewrite和filter规则暂时替换成DivineEngine的规则

* 增加Images文件夹，以备将来用到

* 整合Rewrite文件夹内的内容，使之更加精简直观

## 2021/4/5 变动如下

* 精简配置

* 删除server=114.114.114.114的dns，它会导致添加Task订阅时出现"未能找到使用主机名的服务器"的错误

* 增加去YouTube广告重写远程订阅

* 增加Rewrite文件夹，汇总一些作者的Rule和Cookie地址

------------

## 2021/4/4 变动如下

* 更新README内容

* 修改[filter_remote]和[rewrite_remote]模块中部分[DivineEngine](https://github.com/DivineEngine)规则修改为[blackmatrix7](https://github.com/blackmatrix7)规则

* 在[rewrite_remote]中添加[zwf234](https://github.com/zwf234)的rewrite规则

* 增加Task文件夹，汇总一些作者的Task Gallery地址

-----------

## 2021/4/3 变动如下

* 开始创建QuantumultX仓库

* 以[Orz-3](https://github.com/Orz-3)的小白配置为基础，结合[sngxpro](https://github.com/sngxpro)的懒人配置进行修改
