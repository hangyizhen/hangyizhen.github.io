---
layout:     post
title:      "新工作"
subtitle:   "心情平淡的一天"
date:       2016-07-23
author:     "WangXiaoDong"
header-img: "img/clannad.jpg"
tags:
    - 日记
    - Qt
    - 编译器
---


### 时间:2016年7月23日 天气:晴
-----
#####   Author:冬之晓:stuck_out_tongue_winking_eye:
#####   Email: 347916416@qq.com
#####   MyAppearance: ![MyAppearance](https://github.com/Dongzhixiao/PictureCache/raw/master/MyPicture.JPG "我的头像")
----------
<pre>
    今天晓东教我开博客
</pre>
>Qt5.7.0
>>**5.7**
>>>**mingw53_32**
>>>>**bin**
>>>>>**qmake.exe(将pro文件转换为makefile文件)**

>>dist  
Docs(Qt的说明文档)  
Examples(Qt的示例程序)  
Licenses  
**Tools**
>>>**mingw530_32**
>>>>**bin**
>>>>>**mingw32-make.exe(执行makefile文件来编译所以程序文件)**

>>vcredist  
<pre>
    如上所示，在加粗的路径上的qmake和make是在编译第三方库时比较重要的文件，同
时注意要把系统环境变量里面其他编译器的路径删除，只保留需要编译的qmake版本和mak
e的路径，这样才行！！
</pre>