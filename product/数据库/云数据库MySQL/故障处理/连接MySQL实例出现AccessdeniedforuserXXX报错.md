## 现象描述
连接云数据库 MySQL 实例时，提示“ERROR 1045 (28000): Access denied for user ‘XXX’@’XXX’”报错信息。
![](https://main.qcloudimg.com/raw/3283ffcec33f4bdf02aa6ed8cf48ea48.png)

## 可能原因
1. 用户名错误
2. 主机名错误
3. 密码错误

## 解决思路
检查用户名、主机和密码是否正确。

## 处理步骤
1. 登录 [MySQL 控制台](https://console.cloud.tencent.com/cdb)，在实例列表，找到目标实例，单击实例名，进入实例管理页面。
2. 在实例管理页面，选择【数据库管理】>【帐号管理】页，检查用户名和主机名是否匹配。
![](https://main.qcloudimg.com/raw/5924456fc988241b8aaff93cfe552927.png)
3. 重试密码，确认密码输入无误；如果忘记密码，可找到需要重置密码的帐号，选择【更多】>【重置密码】。
![](https://main.qcloudimg.com/raw/e1a269541a777ee8209fc4a6c5e35cff.png)
 
