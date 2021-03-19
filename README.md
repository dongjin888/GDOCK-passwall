# 根据各位老板的经验学习一下，怎么自定义一个。
这东西就是按套路来，但是…… 套路还是不停出问题。懒的深究了，比较偏门的一个技术
PassWall
SSR+
SmartDNS
SoftEntherVPN

X86_64版本

3.以上修改完后找到workflow文件夹，修改yml文件,即可自动编译固件，就是把yml文件中

找到下面这段
```
on:
     release:
       types: [published]
     # push:  
     #   branches:
     #     - master



上面3行的 # 都删除，就开始编译了。
```

如果你只想使用固件,可以在本项目的actions下下载最新编译的固件.


