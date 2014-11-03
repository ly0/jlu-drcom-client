---------------
### Simple JLU drcom client dirty hack C-version

需要修改 drcom.c 文件中 user(帐号), pass(密码), mac(MAC 地址, 0x010203040506 格式) 等参数,

然后在终端下执行make
	
最后直接在终端运行 ./drcom 即可登陆成功(这个可执行文件可以拷贝到任何目录运行)

PS: 掉线后，drcom会直接退出，等网络连接后，重新运行drcom就行

haha, dirty hack 就是爽 (￣ˇ￣)　

改为以 daemon 方式运行，去掉 long 类型，支持 32 位系统

TODO: logout
