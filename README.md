# go-shellcode-launcher

go从入门到放弃的产物，shellcode本地加载器

用法：

1. 用cs或者msf生成c源码文件把其中的shellcode复制到一个txt里，此处命名为bobo.txt

2. 把bobo.txt和golauncher.exe放入同个文件夹内

3. 执行命令 golauncher.exe bobohacker bobo.txt

其中，bobohacker为运行密码。在源码中是以md5加密存在。```以密码的命名来膜拜一下我的偶像bobo老师```

个人go入门产物仅供学习参考

![image](https://raw.githubusercontent.com/timwhitez/go-shellcode-launcher/master/111.png)
