MetaTrader 4 EA 授权管理程序 
===============
版本：EA_Auth v1.0.1 [点击下载](https://github.com/tanzhenxing/EA_Auth/archive/1.0.1.zip)

## 安装

1. 把 Auth.ex4、 Auth.mql、 hash.mqh、json.mqh 这四个文件复制到 MetaTrader 4\MQL4\Experts 文件夹里

2. 打开 MetaTrader 4 终端程序，把Auth.ex4加载到图表

##  提示
1. 运行EA，需要勾选【dll导入】权限
[![mt4](https://wximg-10001398.file.myqcloud.com/cofan/dll.png)](http://auth.weilian.org.cn/)

2. 如果出现授权不成功的提示，需要你把授权接口url ，修改成你自己的网址。
~~~
把 Auth.mql 文件中的代码
string auth_url = "https://auth.weilian.org.cn/api/auth/verify/key/";
修改成 
string auth_url = "你自己的接口授权网址";

然后重新编译成 Auth.ex4，再加载到图表
~~~

3. /server 目录下的api.php 只是一个接口测试示例
a. 你可以自己开发服务端的接口程序

b. 或者使用我们的EA授权管理系统

## MetaTrader 4 EA 授权展示
[![mt4](https://wximg-10001398.file.myqcloud.com/cofan/mt4.png)](http://auth.weilian.org.cn/)

## 授权管理系统后台界面预览
[![my ht](https://wximg-10001398.file.myqcloud.com/cofan/ht.png)](http://auth.weilian.org.cn/)

## 开发规划
下一个版本计划：增加前台界面
1. 提供会员模块，提供会员登录、注册、会员中心等功能，支持查看会员所属的交易账户列表和对应的授权码、到期时间等。
2. 提供自定义EA功能介绍，效果展示等功能

##  加我微信
获取完整的服务器端授权管理系统程序,以及长期维护、升级服务！

[![my wechat](https://wximg-10001398.file.myqcloud.com/cofan/tan-zhen-xing.jpg)](http://auth.weilian.org.cn/)

##  打赏一下
扫一扫下方二维码，感谢您的支持！
[![my wepay](https://wximg-10001398.file.myqcloud.com/cofan/wepay.jpg)](http://auth.weilian.org.cn/)




