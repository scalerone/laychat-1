# 补充使用说明-2017.09.08
使用back文件夹下最新的laychat.sql请建立数据库，并导入。
此程序配置的是win版的workerman，使用说明参加这里http://www.workerman.net/workerman-chat
本机使用时：
在vendor/Workerman/Applications目录下，按住Shift键，鼠标右键点开cmd窗口
输入php start_register.php start_gateway.php start_businessworker.php
使用两个浏览器，登录不同的前台帐号就可以愉快的聊天了

后台地址：http://域名/admin
帐号/密码：admin/admin
前台登录
帐号/密码：马云/123456
帐号/密码：纸飞机/123456

# laychat-2017.07.20
layIM+workerman+thinkphp5的webIM即时通讯系统 v2.0正式版  

实现了功能:  
1、通过snake后台实现对聊天成员的增删改查，动态推送给在线的用户    
2、实现了群组的查找  
3、实现了创建我的群组,删除我的群组,添加群组成员，移除群组成员  
4、实现了离线用户登录后聊天记录推送  
5、实现了单聊，群聊功能  
6、实现了图片和文件的发送  
7、实现了单聊聊天记录和群聊聊天记录的查看  

# 注意事项:  
back文件夹下有数据库备份文件，请建立数据库，并导入。同时配置项目中的config文件中的datebase.php的数据库信息。  
别忘了vendor/Workerman/Applications/Config/Db.php，workerman的数据库同步跟上。

# 关于LayIM
本项目已可以直接运行但未授权，因为layIM不开源，可以去http://layim.layui.com  这里，layUI的官网去授权吧

# 了解效果
http://www.thinkphp.cn/code/2289.html


