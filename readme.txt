֪ͨ��ʹ�ù���:
a. SystemServer.java : ע��Notification����
b. app��������context���о�̬�飬����ע�����: registerService(NOTIFICATION_SERVICE)
c. app: nm = getSystemService
d. ����Notification
e. ���ò���: ֪ͨ���͡���ɫ��ʱ��
f. nm.notify
   f.1  getService �õ����� "SystemServerע���Notification����"
   f.2 �����ж�֪ͨ���ͽ������õ�֪ͨ�Ƶ�JNI����

0.git init (��һ��ִ�м���)
1.git add -A
2.git commit -m "v1, LIGHTDemo for notification light"
3.git tag v1
4.git remote add origin https://github.com/hujinfan/APP_0002_LIGHTDemo.git ����һ��ִ�м��ɣ�
5.git push -u origin master
6.git push origin --tags

���Ʊ���control backlight
1.git add -A
2.git commit -m "v2, control backlight"
3.git tag v2
4.git push origin master
5.git push origin --tags