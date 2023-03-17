#ionewu 大鹏提速 自动提速工具 Windows程序
根据 https://k.ionewu.com/web/app/ 网页封装，模拟post请求实现定时提速
使用需登陆此页面后从本地cookie处获得UID和OPENID的值后填入程序才能实现定时提速功能

建议间隔时间超过30分钟，避免频繁提交，提交间隔单位为 分钟，留空则不循环
可以修改可执行文件名格式为  123456@abcdefg.exe ，程序运行后会根据 uid@openid.exe 格式自动填入对应位置
