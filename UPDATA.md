# 以下是历史更新记录

## 2021/07/19 变动如下

* 清理部分失效规则

* 替换GetCookie规则，精简数量（很多脚本都不维护了）

## 2021/07/01 变动如下

* 更新[少年歌行pro](https://github.com/Youthsongs/QuanX)地址（地址已失效）

## 2021/06/29 变动如下

* 去除网易云相关规则

* 更换比价相关rewrite规则，修复失效


## 2021/06/10 变动如下

* 微调rewrite下部分规则

## 2021/06/07 变动如下

* 更新“优选节点”策略

## 2021/05/25 变动如下

* 增加ADGuard策略，方便切换

## 2021/05/20 变动如下

* 更新京东、淘宝历史价格

## 2021/05/19 变动如下

* 更新京东历史价格

## 2021/05/18 变动如下

* 京东、淘宝比价已失效，故将其删除

## 2021/05/11 变动如下

* 修改分流规则

## 2021/05/09 变动如下

* 增加网易云音乐策略与TikTok规则

* 在注释中添加[少年歌行pro](https://github.com/sngxpro)与[奇心](https://github.com/zwf234)的task订阅地址（地址已失效）

## 2021/05/08 变动如下

* 换用[ACL4SSR](https://github.com/ACL4SSR)的规则试试

## 2021/05/07 变动如下

* 精简配置，去除自己用不到的策略配置

* 重新试用[blackmatrix7](https://github.com/blackmatrix7)的聚合规则

## 2021/05/05 变动如下

* 增加Toonme重写规则

## 2021/04/25 变动如下

* 增加Guard策略组（感谢[Koolson](https://github.com/Koolson)的图标），方便在获取cookie时暂时停用去广告filter

## 2021/04/17 变动如下

* 跟随[神机](https://github.com/DivineEngine)在general下增添规则

## 2021/04/15 变动如下

* 修改资源解析器地址

* 精简配置

## 2021/04/11 变动如下

* 经过思考，决定放弃[blackmatrix7](https://github.com/blackmatrix7)的聚合规则，误杀现象比较严重，暂时还是不考虑了

* 增加“其余节点”策略，用于汇总其他策略筛选后的

* 更新crack与advertising重写规则，去除配置中[奇心](https://github.com/zwf234)的rewrite规则

* 跟随[契阔](https://github.com/Orz-3)将解析器地址修改为CDN地址，分流地址修改为[神机](https://github.com/DivineEngine)Surge分流文件

## 2021/04/10 变动如下

* 增加Quantumult X 教程

* 修正geo_location_checker内部分国家/地区国旗代码错误

* 将addendum重写补充规则拆分

## 2021/04/09 变动如下

* geo_location_checker忘改了，改一下

* 把[少年歌行pro](https://github.com/sngxpro)的解锁vip规则加回来，但默认关闭（地址已失效）

* 增添补充rewrite配置文件

## 2021/04/08 变动如下

* 去除TikTok重写规则，经常失效，有需要的请自行手动添加

* 将[神机](https://github.com/DivineEngine)的filter规则全部修改为[blackmatrix7](https://github.com/blackmatrix7)的聚合规则

* 将geo_location_checker替换为自己写的脚本（修改自[KOP-XIAO](https://github.com/KOP-XIAO)）

* 上传了两个机场icon

## 2021/04/07 变动如下

* 调整部分规则排列顺序，使之更顺眼

* 增加Task作者订阅地址

* rewrite和部分filter换回[blackmatrix7](https://github.com/blackmatrix7)规则

## 2021/04/06 变动如下

* 精简配置，去除一些不常用的功能

* 暂时去除rewrite模块中[少年歌行pro](https://github.com/sngxpro)的unlockvip订阅（不知道为什么会与今日头条冲突，导致今日头条无法刷新，zwf234的已经能覆盖大部分，盲猜不影响使用体验）（地址已失效）

* 将[blackmatrix7](https://github.com/blackmatrix7)的rewrite和filter规则暂时替换成DivineEngine的规则

* 增加Images文件夹，以备将来用到

* 整合Rewrite文件夹内的内容，使之更加精简直观

## 2021/04/05 变动如下

* 精简配置

* 删除server=114.114.114.114的dns，它会导致添加Task订阅时出现"未能找到使用主机名的服务器"的错误

* 增加去YouTube广告重写远程订阅

* 增加Rewrite文件夹，汇总一些作者的Rule和Cookie地址

------------

## 2021/04/04 变动如下

* 更新README内容

* 修改[filter_remote]和[rewrite_remote]模块中部分[神机](https://github.com/DivineEngine)规则修改为[blackmatrix7](https://github.com/blackmatrix7)规则

* 在[rewrite_remote]中添加[奇心](https://github.com/zwf234)的rewrite规则

* 增加Task文件夹，汇总一些作者的Task Gallery地址

-----------

## 2021/04/03 变动如下

* 开始创建QuantumultX仓库

* 以[Orz-3](https://github.com/Orz-3)的小白配置为基础，结合[少年歌行pro](https://github.com/sngxpro)的懒人配置（地址已失效）进行修改
