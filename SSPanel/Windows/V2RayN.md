# 下载V2rayN

客户端下载地址：[https://www.sstank.tk/ssr-download/v2rayn.zip](https://www.sstank.tk/ssr-download/v2rayn.zip)

下载好了之后，解压，然后打开解压的文件夹
目录结构大概如下图所示，双击运行如下图文件

![1570089391531](https://i.loli.net/2021/01/28/ephQU6XxlLoKFM2.png)

# 导入节点

此处将显示您的订阅链接，请注意为登录状态：

[cinwell website](/sublink?type=v2ray ':include :type=markdown')

您也可以在[主页用户中心](https://www.sstank.ml/user)处，点击如下链接复制订阅地址。

![image-20210128202142365](https://i.loli.net/2021/01/28/T7tvMgacw1U9fbX.png)

!> 这个 **订阅链接** 非常重要，你应当把它当做密码一样妥善保管。

![1570089509627](https://i.loli.net/2021/01/28/tIn9Myjzmo2QGuD.png)

![1570089535265](https://i.loli.net/2021/01/28/Dy2CscKkaBmrMbu.png)

3. 点击更新订阅，会发现出现节点，可以右键**设为活动服务器**，进行节点选择。

![1570089564849](https://i.loli.net/2021/01/28/3yOolqfBXGepWj9.png)

# 开始使用

在任务栏托盘找到 V2RayN 图标并鼠标右键，然后选择 **启动HTTP代理**
并且设置 Http代理模式 -> **全局模式** 或者 **开启PAC，并自动配置PAC**
![1570089692072](https://i.loli.net/2021/01/28/6URDSIiwZBMqg4A.png)

**备注一，如果你浏览器有使用 Proxy SwitchyOmega ，请点击它的图标然后选择 系统代理**
**备注二，如果你在使用 Firefox 浏览器，打开选项，找到网络代理，再选上 使用系统代理**

## 暂停一下

默认来说，使用 V2RayN 的 启动系统代理 来管理翻墙比较简捷一些，浏览器直接就能翻出去了
说着当然，如果你想要手动来管理浏览器的代理也行，往下看
**备注，如果你不是有特别的需求，不需要参考下面的 Firefox 和 Chrome 的做法。**

## Firefox (火狐浏览器)

查看本地的端口，这里以`2333`为例

![1570093735227](https://i.loli.net/2021/01/28/dkJlTGOZ8Qz7DmL.png)

(什么？没有在使用 Firefox ，那赶紧来试用吧，[ Firefox Quantum，更好的浏览器。](https://www.mozilla.org/zh-CN/firefox/) )
打开选项，找到网络代理

![火狐设置代理](https://i.loli.net/2021/01/28/VSr9l4IcRHXizaq.png)

选择手动代理设置，输入 `127.0.0.1 和 2333`，勾选 使用 Socks v5 代理 DNS，然后确定即可。

![设置代理信息](https://i.loli.net/2021/01/28/Etkq267olJvKxaY.png)

OK，此时你已经自由了，赶紧打开 [Google](https://www.google.com/ncr) 找部十八减的大电影喵喵吧。哈哈

## Chrome (谷歌浏览器)
查看本地的端口，这里以`2333`为例

![1570093735227](https://i.loli.net/2021/01/28/dkJlTGOZ8Qz7DmL.png)
安装 Proxy SwitchyOmega （如果你已经安装，知道怎么设置代理吧。。SOCKS5 协议，2333 端口 ）
在线安装：[从 Chrome 应用商店 安装](https://chrome.google.com/webstore/detail/padekgcemlokbadohgkifijomclgjgif)

手动安装如下：
在 Chrome 地址栏输入 **chrome://extensions** 打开扩展程序，之后
下载 [Proxy SwitchyOmega](https://github.com/FelisCatus/SwitchyOmega/releases) ，打开链接后，找到 SwitchyOmega_Chromium.crx 下载，将下载完后的文件拖动到刚才打开的扩展程序的标签进行安装
然后点击 添加扩展程序 即可

![添加扩展程序](https://i.loli.net/2021/01/28/5C6ckEBmjNJGwFe.png)

OK，在完成安装 Proxy SwitchyOmega 后，
浏览器会自动打开一个 SwitchyOmega 选项的窗口，选择跳过教程，

![跳过教程](https://i.loli.net/2021/01/28/m2QYwseZDuafnJM.png)

选择 导入/导出，在线恢复，输入：[ https://github.com/FelisCatus/SwitchyOmega/wiki/GFWList.bak](https://github.com/FelisCatus/SwitchyOmega/wiki/GFWList.bak)

![在线恢复](https://i.loli.net/2021/01/28/nMYJmFKUC9Px8eD.png)

选择 GFWed，设置代理端口为 2333，然后点击 应用选项

![设置代理](https://i.loli.net/2021/01/28/roFIseGuaNVwyHb.png)

然后右上角找到 Proxy SwitchyOmega 图标，点击它，再点击自动切换

![切换代理](https://i.loli.net/2021/01/28/ApgwmZLizIY1UbS.png)

OK，此时你已经自由了，赶紧打开 [Google](https://www.google.com/ncr) 找部十八减的大电影喵喵吧。哈哈

## 结束

实际上，没有特别的需求根本不需要安装 Proxy SwitchyOmega ，直接使用 V2RayN 打开 启动系统代理 就可以自动翻出去了
如果你有使用 Proxy SwitchyOmega
V2RayN 设置的那个 本地鉴听端口 可以随便修改的，如果你修改了，Proxy SwitchyOmega 那边也要设置成对应的端口就行
啊~生活如此美好