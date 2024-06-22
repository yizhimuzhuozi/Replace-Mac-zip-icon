# Replace-Mac-zip-icon
替换 Mac 解压包更换图标

## 前提
![资源 1](https://github.com/yizhimuzhuozi/Replace-Mac-zip-icon/assets/31234254/83082d96-fb22-4cb4-9acf-b8a037cced48)


Mac 本身是不支持 RAR 压缩包（这是由于 RAR 格式不是开源的压缩格式，所以苹果系统自带的解压软件并不支持将RAR文件解压到系统中。）

我自己使用的解压软件是 The Unarchiver，看腻了默认的压缩包图标。发现压缩包的图标可以替换的。找了一圈没找到好看的图标，自己改了几个。

## 1.0

<img width="1263" alt="CleanShot 2023-09-04 at 16 54 02@2x" src="https://github.com/yizhimuzhuozi/Replace-Mac-zip-icon/assets/31234254/8aaee16b-c2c4-4b4d-815b-7d377732e3df">

## 2.0
![](img/2.0.png)

目前只做了 4 个常用图标。**rar、zip、7z、tar**。

## 3.0 新增内容
**exe、jar、bin、ace**

<img width="1694" alt="2024-06-22 at 20 08 13" src="https://github.com/yizhimuzhuozi/Replace-Mac-zip-icon/assets/31234254/bc8be6be-f3f0-4261-b715-487814c5694b">



## 替换

找到 `The Unarchiver—显示包内容—Contents—Resources` 把 icon 替换进去就行了，重启 Mac 就能看到替换好的图标。

需要注意的是你的默认解压软件必须是 The Unarchiver 如果不是你替换了也没用。我测试了 The Unarchiver、BetterZip 都是可以生效的。

![CleanShot 2023-09-04 at 16 56 37@2x](https://github.com/yizhimuzhuozi/Replace-Mac-zip-icon/assets/31234254/636e33f7-d0e5-4808-80c7-d576abc7a5c8)


