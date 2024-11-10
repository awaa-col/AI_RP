!!! warninig "本部分教程因为作者没有设备,故基于宝宝辅食修改"
    宝宝辅食对应文章连接:https://sqivg8d05rm.feishu.cn/wiki/EY5TwjuwliCwZpk7Gy7cPGH1nvb
    本部分采用的是喵喵一键安卓部署脚本,赞美大佬!!!

# 下载教程
- Termux 下载
    - 原作者链接(123盘): https://www.123pan.com/s/P8OAjv-Glhtv.html Claude -> 安卓 -> Termux(优先) ->下载
    - 教程整合者打包链接: https://1drv.ms/u/s!AuYOZOGOoRhagkd_EiL_PTmWmnBW?e=65SmgR
- 安装并启动 Termux

    !!! warning "请想办法保持住Termux的后台"
        可以使用锁后台
        若为华为/荣耀,则手机管家 -> 启动管理 -> Termux设置为手动管理 -> 勾选允许后台活动
- 输入以下内容,回车,等待脚本运行完毕```curl -O https://raw.githubusercontent.com/hopingmiao/termux_using_Claue/main/tisac.sh && chmod +x tisac.sh && ./tisac.sh```
- 配置 - Clewd
    - 输入"3",选择修改Clewd设置,再选择Cookie添加,填完所有Cookie(可直接将从商家那买的Cookie + 邮箱 +密码 的文本填入),回车,Ctrl + D 退出
    - 输入"1"启动Clewd,黄色网址(通常为http://127.0.0.1:8444/v1)为反代链接
- 配置 - ST
    - 等待部署完毕后,输入2,等待绿色网址出现(通常为http://127.0.0.1:8000)
    - 进入绿色网址,填写用户名(这是你聊天中发送给AI的名字),**不要勾选Enable Simple UI Mode**,这将导致功能缺失
    - 随后按照ST配置的方法[配置ST](RP/Claude/配置ST)

!!! failure "叠甲"
    整合者没有安卓设备可以测试安卓部署脚本!!!
    实际操作需要补充