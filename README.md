# windsurf-vip

> 🌐️ English | [中文](README_CN.md)

`windsurf-vip` is a tool service for Windsurf smart code editor to enjoy VIP intelligent prompts without logging in.


### Usage

Open the terminal on MacOS/Linux; Open Git Bash on Windows. Then execute the following command to install:
>some computers may report false positives, need to close the antivirus software/computer housekeeper/security protection and then proceed

Method 1: Install via GitHub script
```bash
bash <(curl -Lk https://github.com/kingparks/windsurf-vip/releases/download/latest/i.sh) githubReadme
```
Method 2: Install via ghp.ci proxy script
```bash
bash <(curl -Lk https://ghp.ci/https://github.com/kingparks/windsurf-vip/releases/download/latest/install.sh) githubReadme
```
Method 3: Manually download the binary file
> download the binary file for the corresponding operating system from the [release](https://github.com/kingparks/windsurf-vip/releases) page
 ```shell
# MaxOS/Linux
sudo mv windsurf-vip_xx_xxx /usr/local/bin/windsurf-vip;
chmod +x /usr/local/bin/windsurf-vip;
windsurf-vip githubReadme;
# Windows 
# double click windsurf-vip_xx_xxx.exe
```

Launch windsurf-vip：
```bash
# MaxOS/Linux
windsurf-vip
# Windows
# double click windsurf-vip_xx_xxx.exe
```

<!--
<details>
<summary>Precautions for using strong proxy mode</summary>

Strong proxy mode For the first time after starting, you need to install the trusted certificate. The certificate will be automatically generated after the first start command, and the path is `~/.windsurf-vip/windsurf-vip-ca-cert.pem`.
* MacOS: Execute `open ~/.windsurf-vip` in the terminal, double-click the windsurf-vip-ca-cert.pem file, pop up the "Keychain Access" window, select the certificate, search for windsurf-vip, double-click windsurf-vip, expand trust, select "Always trust when using this certificate", close the pop-up window, enter the password to confirm, and the certificate is installed.
* Windows: Search for cer in windows, select the `certmgr.msc` function, expand `Trusted Root Certification Authorities`, select `Certificates`, right-click `All Tasks`, select `Import...`, next, enter the `%homepath%\.windsurf-vip\windsurf-vip-ca-cert.pem` file, next all the way, complete; reopen the browser.
* Linux: //TODO linux currently only supports minimalist mode

</details>
-->

Enjoy windsurf-vip:
* Open the Windsurf code editor, click the settings icon in the upper right corner, and you can see that you are already a VIP account.
* Enjoy code prompts and chat functions.

---
### Promotion Guide
By promoting windsurf-vip, you can automatically get up to an unlimited amount of free usage time, and the other party can also get 15 days of free (self-registration for 7 days), you can refer to the following methods:
1. After cloning this repository, replace `githubReadme` in the `README` with your DeviceID.
2. Post articles on platforms such as SegmentFault/Stack Overflow/GitHub Discussions/Reddit/Dev.to/Hacker News/DZone/V2EX/Quora/WeChat Official Account/Zhihu/Bilibili/CSDN/, promoting the use of windsurf pro in this way, and attach your own promotional installation command or cloned github address.
3. Comment under Windsurf related articles or videos, for example: "Cooperate with Github's [Your Github Name]/windsurf-vip for low-priced or freelancing Pro"
---
### Star History
<a href="https://star-history.com/#kingparks/windsurf-vip&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=kingparks/windsurf-vip&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=kingparks/windsurf-vip&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=kingparks/windsurf-vip&type=Date" />
 </picture>
</a>