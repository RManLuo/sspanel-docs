## 应用概述

Shadowrocket 是在 iOS 平台上的客户端软件，支持 Shadowsocks、ShadowsocksR 以及 VMess 协议。

目前 Shadowrocket 已经被 Apple 根据政府要求从中国大陆区的 App Store 移除，之前在中国大陆商店购买此软件的用户将不能获得更新或重新下载，因此需要切换账号进行下载。

## 切换账号并下载软件

1. 可以先尝试在[首页](https://www.sstank.ml/user)获取共享账户，如果共享账户需要验证码可以联系QQ:740827790，如果首页共享账户被锁定无法使用，可以从此链接购买ios[账号](http://iosid.cn/index.php?html=1)使用。

   ![image-20210128200225899](https://i.loli.net/2021/01/28/wITuEhgvZ8KRLca.png)

2. 在IOS商店切换成该账户（为保证您的设备安全，请在下载软件之后切回自己的账户）

   登录教程：点开**App Store**->点**头像**->最下面点**退出登录**->输入**账号密码**进去点**登录**->登陆后搜索**Shаdоwroсκet** 找到一个白色的小火箭下载就行（有时网络不稳定，要是还显示**2.99$**输入密码**购买**消费即可）

   要是登录了搜索不到，在**已购项目**里最底下就是

   ![img](https://i.loli.net/2021/01/28/QxDIb5gi2sXulBR.jpg)

   下载好小火箭后，进入**App Store**点**头像**->滑到最下面点**退出登录(Sign out)**，然后登录你自己的账号，长时间不退出手机会锁！

3. 搜索**Shadowrocket**，并下载

   ![1570092704540](https://i.loli.net/2021/01/28/2ZlpwqyW1Vi4r8k.png)



## 获取订阅

此处将显示您的订阅链接，请注意为登录状态：

[cinwell website](/sublink?type=shadowrocket ':include :type=markdown')

您也可以在[主页用户中心](https://www.sstank.ml/user)处，点击如下链接复制订阅地址。

![image-20210128202142365](https://i.loli.net/2021/02/01/Ddt2QTgLsexq46R.png)

!> 这个 **订阅链接** 非常重要，你应当把它当做密码一样妥善保管。

## 配置 Shadowrocket

打开 Shadowrocket，点击底部导航栏的「设置」进入设置页面，随后往下划至最底部，进入「服务器订阅」子页面。

将「打开时更新」的开关 **打开**。

![1](https://i.loli.net/2019/01/13/5c3a5bee38465.jpeg ':size=600')

**回到首页**，点击右上角的加号，再次点击第一行的「类型」，选择 **Subscribe**。

![2](https://i.loli.net/2019/01/13/5c3a5ddd2f5bf.jpeg ':size=600')

在「备注」中输入本站名称，随后在「URL」中粘贴上方 **[获取订阅](#获取订阅)** 中您需要使用的订阅类型并保存。

![3](https://i.loli.net/2019/01/13/5c3a5edd7c257.jpeg ':size=200')

随后点击右上角保存，此时会自动更新获取服务器。

可以看到出现了节点，把全局路由调成代理模式，选择节点连接即可

   ![1570092747469](https://i.loli.net/2021/01/28/yVLoRjq9IPdnJTD.png)

记得允许创建VPN

   ![1570092851888](https://i.loli.net/2021/01/28/a5zU9D4MTw3cI2h.png)
## 开始使用

回到 Shadowrocket 首页，在订阅组中选择您需要的节点，随后打开第一行开关即可。

如提示添加 VPN 配置，请点击 Allow 并验证您的 密码、Touch ID、Face ID 。

## 自动更新订阅
为了更方便的获取服务端信息变更，我们强烈建议iOS使用shadowrcoket (即：小火箭)的用户打开自动更新订阅，打开方式如下：

1. 找到Shadowrocekt设置页面，如图所示

![img](https://i.loli.net/2021/01/28/tS6MLBN2IeuJAfo.png)

2. 点击服务器订阅，进入如图所示。

![img](https://i.loli.net/2021/01/28/EM7vFAIwncJW2sj.png)

3. 打开时更新即可，完成后每次启动会自动更新订阅

## 分流规则（此章节属于高阶用法，可以不看）

> 此章节可以教您通过软件自动切换是否使用vpn，不会在打开vpn的情况下影响您访问国内网络的速度。

在底部导航栏进入「配置」页面，点击右上角加号。

在弹出的输入框中输入「<https://raw.githubusercontent.com/Hackl0us/Surge-Rule-Snippets/master/LAZY_RULES/Shadowrocket.conf>」可长按链接拷贝，并点击下载。

随后点击 **远程文件** 中新增的配置文件地址，在弹出的菜单中选择第二个「使用配置」，此时 APP 会自动开始下载配置并应用配置。

![4](https://i.loli.net/2019/01/13/5c3a615f60e87.png ':size=600')

**回到首页**，点击进入「全局路由」将其更改为 **配置**。

![5](https://i.loli.net/2019/01/13/5c3a63f4adce6.jpeg ':size=400')
