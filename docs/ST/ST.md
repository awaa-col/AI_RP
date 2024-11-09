# 什么是Silly Tavern
这是用来进行角色扮演的重要工具,我们称其为
- ST
- 酒馆

# 如何部署 Silly Tavern
使用一键包:
- Win + R 打开运行
- 输入 cmd 随后回车
- Git 安装(若有,则跳过): 
    - 将以下内容复制进CMD : ```cmd /c winget install -e --id Git.Git```,在要求输入内容时直接输入 y 并回车
    
- ST 安装
    - 将以下内容再次复制进CMD并回车:
    ```
    cd Desktop
    git clone https://github.com/SillyTavern/SillyTavern-Launcher.git && cd SillyTavern-Launcher && start installer.bat
    ```
    或
        ```
    cd Desktop
        git clone https://gitclone.com/github.com/SillyTavern/SillyTavern-Launcher && cd SillyTavern-Launcher && start installer.bat
    ```


使用一键包:
- Win + R 打开运行
- 输入 cmd 随后回车
- Node Js 安装(若有,则跳过)
    - 复制,输入进CMD并回车
    ```
    curl -o node-v22.11.0-x64.msi https://nodejs.org/dist/v22.11.0/node-v22.11.0-x64.msi
    msiexec /i node-v22.11.0-x64.msi

    ```
    - 在弹出的窗口内点击方框,随后一直点击next
- Git 安装(若有,则跳过): 
    - 将以下内容复制进CMD : ```cmd /c winget install -e --id Git.Git```,在要求输入内容时直接输入 y 并回车
- ST 安装 
    - 将以下内容输入CMD
    ```
    CD desktop
    git clone https://github.com/SillyTavern/SillyTavern.git
    ```
    或
    ```
    CD desktop
    git clone https://gitclone.com/github.com/SillyTavern/SillyTavern
    ```
如果不出意外的话,您可以正常使用ST了
