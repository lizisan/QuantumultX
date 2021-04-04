# Quantumult X  —— A Powerful Network Tool

## Quantumult X 教程

&nbsp;&nbsp;&nbsp;下面是搜集的一些Quantumult X 教程

* [Quantumult X 不完全教程](https://www.notion.so/Quantumult-X-1d32ddc6e61c4892ad2ec5ea47f00917#4cd9bf57eb914320baa0956ee7f50fc0https://www.notion.so/Quantumult-X-1d32ddc6e61c4892ad2ec5ea47f00917#4cd9bf57eb914320baa0956ee7f50fc0)

## 使用说明

### 一、订阅基础配置

&nbsp;&nbsp;&nbsp;1.点击库中的"lizisan.conf"文件(移动端先点View code打开库里的文件列表)，点击"raw"获取真实地址，复制地址备用

&nbsp;&nbsp;&nbsp;2.打开Quantumult X，轻点右下角风车图标，打开设置菜单，然后将菜单下拉至最底端，选择“配置文件-下载”
 
&nbsp;&nbsp;&nbsp;3.将第1步复制的订阅地址粘贴进去，选确定，此时弹出订阅后添加进去的配置文件，点右上角的保存按钮保存即可

&nbsp;&nbsp;&nbsp;4.回到Quantumult X的设置菜单，找到"MitM"页面，依次点击"生成证书"→"配置证书"，根据提示安装证书

&nbsp;&nbsp;&nbsp;5.安装证书成功后启用证书，并来到手机的"设置-通用-关于本机--证书信任设置"中，启用Quantumult X的根证书

&nbsp;&nbsp;&nbsp;6.回到Quantumult X的设置菜单，打开"重写"与"MitM"功能

&nbsp;&nbsp;&nbsp;7.基础配置订阅完成

### 二、订阅任务(task)配置

&nbsp;&nbsp;&nbsp;1.复制你想订阅的task订阅地址(方法同上文，task订阅地址请自行寻找，这里暂不提供)

&nbsp;&nbsp;&nbsp;2.打开Quantumult X，在设置菜单中找到调试，选择构造请求并进入(也可向左轻滑风车，点击三道杠样式的图标)

&nbsp;&nbsp;&nbsp;3.在构造请求界面，点击右上方第一个图标(像是三个菱形摞在一起)

&nbsp;&nbsp;&nbsp;4.弹出界面点加号，将之前选中的仓库订阅地址复制粘贴进来

&nbsp;&nbsp;&nbsp;5.点击"好"，即可看到出现了新建仓库及任务图标

### 三、订阅分流(filter)及重写(rewrite)配置

&nbsp;&nbsp;&nbsp;1.方法与上文类似，请参考一、二进行配置(订阅地址请自行寻找，这里暂不提供)

## 注意事项

* 配置更新<br>
  请事先备份[server_remote]，[server_local]和[mitm]下的内容，如果自己做了其他更改也一样备份，然后重新导入新的配置，将备份的内容粘贴回去
* BoxJS<br>
  BoxJS请访问http://127.0.0.1:9999/  其他问题请进[BoxJS官方文档](https://chavyleung.gitbook.io/boxjs/)了解

## 更新历史

https://github.com/lizisan/QuantumultX/blob/main/Updata.md

## 致谢

  * [crossutility](https://github.com/crossutility)

  * [KOP-XIAO](https://github.com/KOP-XIAO)

  * [Orz-3](https://github.com/Orz-3)

  * [sngxpro](https://github.com/sngxpro)

  * [DivineEngine](https://github.com/DivineEngine)
  
  * 由于参考或借用上述作者内容而导致直接或间接引用的各位作者大大


## 免责声明：

* lizisan发布的相关项目中涉及的任何内容仅用于资源共享和学习研究，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。

* 间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播, lizisan对于由此引起的任何隐私泄漏或其他后果概不负责。

* 请勿将本项目的任何内容用于商业或非法目的，否则后果自负。

* 如果任何单位或个人认为该项目可能涉嫌侵犯其权利，则应及时通知并提供身份证明或所有权证明，我们将在收到认证文件后删除相关脚本。

* lizisan对任何项目问题概不负责，包括但不限于由本项目任何内容导致的任何损失或损害。

* 您必须在下载或使用后的24小时内从计算机或手机中完全删除以上内容。

* 任何以任何方式查看此项目的人或直接或间接使用该项目的任何内容的使用者都应仔细阅读此声明。

* lizisan保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关项目内容的规则，则视为您已接受此免责声明。
