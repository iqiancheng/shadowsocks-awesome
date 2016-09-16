# shadowsocks-gfwlist
一个实时更新的实用gfwlist清单。不需要借助插件实现Shadowsocks国内外网站的PAC自动分流。 
- 用于无障碍科学上网
- 请自备``shadowsocks``账号密码
- 不需要给浏览器安装类似``SwitchyOmega``这样的插件
- 用户不需要关心自己上的网站是在墙外还是墙内，流畅上网


# Usage
## for Windows
**下载客户端**

在``client``分支下载 ``Shadowsocks-win-3.x.zip`` 解压，并配置``server``填入您的服务器用户名密码

**设置shadowsocks-gfwlist**

![](https://raw.githubusercontent.com/iqiancheng/shadowsocks-awesome/doc/images/ss-setting-003.png "Shadowsocks client for windows settings")

像上图这样设置shadowsocks，使用PAC模式;

![](https://raw.githubusercontent.com/iqiancheng/shadowsocks-awesome/doc/images/ss-setting-001.png "Shadowsocks client for windows settings")

PAC选项为Local PAC（本地pac文件）。 

![](https://raw.githubusercontent.com/iqiancheng/shadowsocks-awesome/doc/images/ss-pac-setting-002.png "Shadowsocks client for windows settings")

然后下载当前分支下的pac.txt文件，放在Shadowsocks.exe同级根目录下，启动即可。

## for Mac
苹果Mac用户，则把当前分支下 ``.Shadowsocks`` 文件夹,放在当前用户的根目录 ``~/`` 。

**下载客户端**

在``client``分支下载 ``shadowsocks.dmg`` 安装

**设置shadowsocks-gfwlist**

```bash
$ cp -R .Shadowsocks ~/
```


