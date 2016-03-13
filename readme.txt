通知灯使用过程:
a. SystemServer.java : 注册Notification服务
b. app的上下文context里有静态块，它会注册服务: registerService(NOTIFICATION_SERVICE)
c. app: nm = getSystemService
d. 构造Notification
e. 设置参数: 通知类型、颜色、时间
f. nm.notify
   f.1  getService 得到的是 "SystemServer注册的Notification服务"
   f.2 最终判断通知类型进而调用到通知灯的JNI函数

0.git init (第一次执行即可)
1.git add -A
2.git commit -m "v1, LIGHTDemo for notification light"
3.git tag v1
4.git remote add origin https://github.com/hujinfan/APP_0002_LIGHTDemo.git （第一次执行即可）
5.git push -u origin master
6.git push origin --tags

控制背光control backlight
1.git add -A
2.git commit -m "v2, control backlight"
3.git tag v2
4.git push origin master
5.git push origin --tags