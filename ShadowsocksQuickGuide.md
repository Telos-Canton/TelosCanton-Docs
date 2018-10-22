# Shadowsocks使用简明指引

## 1. Windows & MacOS
### 1.1. 基本配置
a. 解压“Chrome科学上网_解压密码123.zip”压缩包（注意解压密码是123）；
b. Windows操作系统：复制“Windows+Chrome+Shadowsocks”中的“Shadowsocks”目录到C盘任意目录。点  击“Shadowsocks”目录中的“Shadowsocks.exe”启动软件；
​    MacOS操作系统：在菜单栏依次点击“前往”→“应用程序”，将“MacOS+Chrome+Shadowsocks”中的“ShadowsocksX-NG.zip”拖到“应用程序”中，点击启动软件；
c. Windows操作系统：在任务栏右下角找到“Shadowsocks”图标（纸飞机），右击选择“服务器”再点击“编辑服务器”；服务器IP、服务器端口和密码按提供的资料填写；
​    MacOS操作系统：在顶栏找到“Shadowsocks”图标（纸飞机）， 右击选择“服务器”再点击“编辑服务器”；服务器IP、服务器端口和密码按提供的资料填写；
d. Google或百度搜索Chrome浏览器，下载并安装；
e. 点击浏览器右上角选项栏，选择“更多工具”，再点击“扩展程序”，或者在地址栏输入：chrome://extensions/
g. 将压缩包解压出的“SwitchyOmega.crx”拖到扩展程序窗口会显示“拖放以安装”，松开鼠标完成安装；
h. 右击浏览器右上角的“SwitchyOmega”图标（黑色的圆圈），选择“选项”，再选择“导入/导出”，点击“从备份文件恢复”，选择压缩包解压出的“OmegaOptions.bak”完成配置导入；
i. 左击浏览器右上角的“SwitchyOmega”图标，选择“Auto in China”，程序会根据访问的网址自动切换代理或直接连接；而选择“Shadowsocks”则全部使用代理访问网站。

### 1.2. 进阶使用
a. 最新客户端官网下载：https://shadowsocks.org/en/download/clients.html
b. 如果除浏览器外的其他软件需要使用Shadowsocks联网，可以右击“Shadowsocks”图标（纸飞机）选择“启用系统代理”，再选择“系统代理模式”中的“PAC模式”或“全局模式”。
- PAC模式：只有被封锁的域名和IP才通过Shadowsocks访问；
- 全局模式：所有网络通讯都通过Shadowsocks代理。
### 1.3. 常见问题
使用Windows系统按上述指导启动软件仍然无法上网，可能缺少如下组件：
- [ ] Microsoft .NET Framework 4.6.2 or higher
  https://www.microsoft.com/en-US/download/details.aspx?id=53344
- [ ] Microsoft Visual C++ 2015 Redistributable (x86) 
  https://www.microsoft.com/en-us/download/details.aspx?id=53840
请下载上面两个组件并完成安装后使用。

## 2. Android
a. 解压“Chrome科学上网_解压密码123.zip”压缩包（注意解压密码是123）；
b. 复制“”目录中的“”到Android手机任意目录，安装应用；
c. 启动Shadowsocks应用，

## 3. iOS
a. 在Apple Store安装Outline应用
b. 在Windows或MacOS的配置好服务器的Shadowsocks上选择“服务器”再点击“分享服务器配置”，