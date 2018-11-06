# Shadowsocks 简明使用指南

## 1. Windows & MacOS
### 1.1.  基本配置
a. 解压“[科学上网-解压密码是123.zip](https://github.com/Telos-Canton/TelosCanton-Docs/raw/master/software/%E7%A7%91%E5%AD%A6%E4%B8%8A%E7%BD%91-%E8%A7%A3%E5%8E%8B%E5%AF%86%E7%A0%81%E6%98%AF123.zip)”压缩包（注意解压密码是123）；  
b. Windows 操作系统：复制“Windows+Chrome+Shadowsocks”中的“Shadowsocks”目录到C盘任意目录。点击“Shadowsocks”目录中的“Shadowsocks.exe”启动软件；  
​    MacOS 操作系统：在菜单栏依次点击“前往”→“应用程序”，将“MacOS+Chrome+Shadowsocks”中的“ShadowsocksX-NG.zip”拖到“应用程序”中，点击启动软件；  
c. Windows 操作系统：在任务栏右下角找到“Shadowsocks”图标（纸飞机），右击选择“服务器”再点击“编辑服务器”；  
​    MacOS 操作系统：在顶栏找到“Shadowsocks”图标（纸飞机）， 右击选择“服务器”再点击“编辑服务器”；  
d. 服务器IP、服务器端口和密码按提供的资料填写，加密方式选择“aes-256-cfb”；  
e. Google 或百度搜索 Chrome 浏览器，下载并安装；  
f. 点击浏览器右上角选项栏，选择“更多工具”，再点击“扩展程序”，或者在地址栏输入：chrome://extensions/  
g. 将压缩包解压出的“SwitchyOmega.crx”拖到扩展程序窗口会显示“拖放以安装”，松开鼠标完成安装；  
h. 右击浏览器右上角的“SwitchyOmega”图标（黑色的圆圈），选择“选项”，再选择“导入/导出”，点击“从备份文件恢复”，选择压缩包解压出的“OmegaOptions.bak”完成配置导入；  
i. 点击浏览器右上角的“SwitchyOmega”图标，选择“Auto in China”，程序会根据访问的网址自动切换代理或直接连接；而选择“Shadowsocks”则全部使用代理访问网站。

### 1.2.  进阶使用
a. 最新客户端官网下载：https://shadowsocks.org/en/download/clients.html  
b. 如果除浏览器外的其他软件需要使用 Shadowsocks 联网，可以右击“Shadowsocks”图标（纸飞机）选择“启用系统代理”，再选择“系统代理模式”中的“PAC模式”或“全局模式”。

- PAC 模式：只有被封锁的域名和IP才通过 Shadowsocks 访问；
- 全局模式：所有网络通讯都通过 Shadowsocks 代理。
### 1.3.  常见问题
a. 使用 Windows 系统按上述指引启动软件仍然无法上网，可能缺少如下组件：
- Microsoft .NET Framework 4.6.2 or higher
  https://www.microsoft.com/en-US/download/details.aspx?id=53344
- Microsoft Visual C++ 2015 Redistributable (x86) 
  https://www.microsoft.com/en-us/download/details.aspx?id=53840
  请下载上面两个组件并完成安装后使用。

b. 遇到无法访问的网站，可尝试从“Auto in China”切换到“Shadowsocks”。或点击浏览器右上角的“SwitchyOmega”图标，选择“选项”，点击左侧的“Auto in China”，在切换规则栏底部点击“添加条件”，将无法访问网站的域名连通配符一并添加上去（如：*.abc.com），情景模式选择“Shadowsocks”，点击左侧的“应用选项”保存。

## 2. Android
a. 解压“[科学上网-解压密码是123.zip](https://github.com/Telos-Canton/TelosCanton-Docs/raw/master/software/%E7%A7%91%E5%AD%A6%E4%B8%8A%E7%BD%91-%E8%A7%A3%E5%8E%8B%E5%AF%86%E7%A0%81%E6%98%AF123.zip)”压缩包（注意解压密码是123）；  
b. 复制“Android”目录中的“Shadowsocks.apk”到Android手机任意目录（也可以到官网下载，网址如1.2.所示），安装应用；  
c. 启动 Shadowsocks 应用，按右上角的加号，选择“手动设置”，服务器IP、服务器端口和密码按提供的资料填写，加密方式选择“aes-256-cfb”，点击勾号保存配置；  
d. 选择已保存的服务器，按右下角的“纸飞机”启动代理服务。

## 3. iOS
a. 在 Apple Store 安装 Outline 应用；  
b. 按照上面的指引，根据提供的服务器资料，配置好 Windows 或 MacOS 上的 Shadowsocks 程序；  
c. 在 Windows 或 MacOS 配置好的 Shadowsocks 程序上选择“服务器”再点击“分享服务器配置”，复制弹出二维码下方以“ss://”开头的字符串，保存或发送到手机能获取的地方；  
d. 打开 Outline 应用，点击右上角的加号，粘贴上一步获取的字符串，添加服务器；  
e. 按已添加服务器下方的“连接”启动代理服务。