!!! failure "本处指代的Clewd为Clewd修改版!!!"
# 什么是Clewd
Clewd是一个十分方便的为Claude Cookie优化的反向代理,是使用Claude Cookie进行角色扮演的重要工具

# 如何部署Clewd?
**Clewd需要在Node Js环境下部署,Node Js下载请参考[占位]**

# Node Js 安装(若有,则跳过)
Win + R 输入CMD并回车,将以下内容复制到CMD内
```
curl -o node-v22.11.0-x64.msi https://nodejs.org/dist/v22.11.0/node-v22.11.0-x64.msi
msiexec /i node-v22.11.0-x64.msi

```
在弹出的窗口内点击方框,随后一直点击next

## 使用Git进行安装(推荐)
**以下命令将把Clewd安装到桌面**
使用Git安装

Git 安装:

将以下内容复制进CMD : ```cmd /c winget install -e --id Git.Git```
在要求输入内容时直接输入 y 并回车


Github(官网)
```
cd %USERPROFILE%\Desktop
git clone https://github.com/teralomaniac/clewd.git
```
Github(下载加速站)
```
cd %USERPROFILE%\Desktop
git clone https://gitclone.com/github.com/teralomaniac/clewd
```
## 使用ZIP安装(不推荐)
[Clewd修改版(打包于2024年11月5日)](https://1drv.ms/u/s!AuYOZOGOoRhagkb11nIwaSTVV1tl?e=BsZ61B)
下载完毕后解压到您想解压到的地方

# 配置Clewd
!!! warning "请确保您安装了Node Js"

- 双击 Clewd 文件夹
- 双击 "start.bat"
- 关闭窗口并右键多出来的"config.js",选择用记事本打开
- 将您的"Cookie"以["Cookie1","Cookie2"]的格式放入CookieArray中
- 使用Ctrl + S 保存记事本文件后关闭窗口
- 配置完毕

# 启动Clewd
双击start.bat,若页面出现类似内容,则部署成功
![alt text](image.png)

# 常见报错
- 在启动时报错 403 - 检查您能否正常登录[Claude官网](https://claude.ai),若不能,则切换节点为能进入Claude官网的节点
- 启动后聊天中报 403 - Cookie被封禁/网络问题
- 429 - 超出使用限制,等待ST的 AI输出的时间结束后就可以继续使用
- 413 - 提示词过长,若您不是Claude Pro Cookie用户,请在ST的预设页面将上下文长度设置为10000-25000之间
- NULL - 您的Cookie被封禁
- Overlap - 重复的Cookie,不需要管这个
- 200,但是空回复 - 网络波动/A社服务器抽风,重新发送消息
- undefined - 网络波动,重新发送消息
