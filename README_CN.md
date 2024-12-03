# windsurf-vip

> 🌐️ 中文 | [English](README.md)

`windsurf-vip` 是一个用于 windsurf 智能代码编辑器 无需账号登录即可享受VIP智能提示的工具服务。


### 使用方式

在 MacOS/Linux 中，请打开终端；在 Windows 中，请打开 Git Bash。然后执行以下命令来安装：
> 部分电脑可能会误报毒，需要关闭杀毒软件/电脑管家/安全防护再进行

方式1：通过 ghp.ci 代理脚本
```bash
bash <(curl -Lk https://github.com/kingparks/windsurf-vip/releases/download/latest/i.sh) githubReadme
```
方式2：通过 GitHub 脚本
```bash
bash <(curl -Lk https://ghp.ci/https://github.com/kingparks/windsurf-vip/releases/download/latest/install.sh) githubReadme
```
方式3：手动下载二进制文件
> 从 [release](https://github.com/kingparks/windsurf-vip/releases) 页下载对应操作系统的二进制文件
```shell
# MaxOS/Linux
sudo mv windsurf-vip_xx_xxx /usr/local/bin/windsurf-vip;
chmod +x /usr/local/bin/windsurf-vip;
windsurf-vip githubReadme;
# Windows
# 双击 windsurf-vip_xx_xxx.exe
```

启动 windsurf-vip：
```bash
# MaxOS/Linux
windsurf-vip
# Windows
# 双击 windsurf-vip_xx_xxx.exe
```

<!--
<details>
  <summary>使用强劲代理模式注意事项</summary>

如果选择强劲代理模式首次启动后需安装信任证书，证书会在首次启动命令后自动生成，路径为 `~/.windsurf-vip/windsurf-vip-ca-cert.pem`。
* MacOS: 在终端执行 `open ~/.windsurf-vip`，双击 windsurf-vip-ca-cert.pem 文件，选择`登录`，弹出“钥匙串访问”窗口，选择证书，搜索 windsurf-vip，双击 windsurf-vip，展开信任，选择使用此证书时“始终信任”，关闭弹窗，输入密码确认，证书安装完成。
* Windows: 在windows搜索输入 `管理用户证书`,选择`管理用户证书`功能，展开`受信任的根证书颁发机构`，选中`证书`，右键`所有任务`，选择`导入`，下一步，输入`%homepath%\.windsurf-vip\windsurf-vip-ca-cert.pem`文件，一直下一步，完成; 重新打开浏览器。
* Linux: //TODO linux 目前只支持极简模式

</details>
-->

享受 windsurf-vip：
* 打开 windsurf 代码编辑器，点击右上角设置图标，可看到已是VIP账号。
* 尽情享受代码提示和聊天功能。
---
### 推广指南
通过推广 windsurf-vip，您可以自动获得至多无限多的免费使用时间,对方也可以获取15天的免费试用(自主注册为7天), 可参考以下方式：
1. clone 该仓库后，替换 `README` 中的 `githubReadme` 为您的设备码。
2. 在公众号/知乎/哔哩哔哩/CSDN/SegmentFault/Stack Overflow/GitHub Discussions/Reddit/Dev.to/Hacker News/DZone/V2EX/Quora 等平台发布文章，安利此种使用 windsurf pro 的方式，附加上自己的推广安装命令或 clone 后的 github 地址。
3. 在相关 windsurf 文章或视频下面评论 例如："可以配合 github 的 [你的github名字]/windsurf-vip 低价或白嫖 Pro"
---
### Star History
<a href="https://star-history.com/#kingparks/windsurf-vip&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=kingparks/windsurf-vip&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=kingparks/windsurf-vip&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=kingparks/windsurf-vip&type=Date" />
 </picture>
</a>