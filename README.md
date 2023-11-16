# SEU-lecture-helper
# SEU研究生讲座预约助手
能够在PC端SEU网上办事服务大厅的研究生素质讲座实现自动定时抢讲座，可以做到自动或者手动输入验证码，解放双手！

### 下载

[安装SEU研究生讲座预约助手](https://raw.githubusercontent.com/Cliencer/SEU-lecture-helper/master/code.user.js)

需要安装[油猴插件](https://www.tampermonkey.net/) 才能运行。

### 验证码api账户配置
由于脚本需要自动获取验证码图片，并识别验证码，因此选用超级鹰接口服务。其账户配置过程如下：

1. 访问 http://www.chaojiying.com/ ，注册账号，充值1元作为接口费用。
2. 进入个人中心 > 软件ID，申请一个软件ID。
3. 将用户名，密码，软件ID分别填入到脚本设置栏中保存即可。

### 鸣谢
本脚本制作思路来自[404874351](https://github.com/404874351)/[seu-lecture-reserve](https://github.com/404874351/seu-lecture-reserve)
