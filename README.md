#url更新日期2022.05.16
#API获取url修改为手动
自行抓包后替换jx_cfd_dh.py中的new_url ="xxx"

一、
#### 拉库命令
```
ql repo https://github.com/nkym233/Script.git "jx_" "" "ql_"
```

国内网络不通可以试下面这个
```
ql repo https://git.wej.cc/github.com/nkym233/Script.git "jx_" "" "ql_"
```
二、
#### 添加环境变量
名称:CFD_COOKIE
</br>
值:ck格式:
pt_key=xxx;pt_pin=xxx;cid=1;

ps:别忘记末尾的cid=1;

