@[TOC](目录)

# 🔥LabelImg

首先打开👉[fffff](https://www.scut-robotlab.cn/nextcloud/index.php/s/qsezS7W5yNMatML)，  
![下载页面](https://github.com/V-9318/labelImg/raw/master/1.png)  
打开之后是这样：  
![👊](https://github.com/V-9318/labelImg/raw/master/2.png)  
下载后选择④⑨-⑦⑧之内的数字，④⑨-⑦⑧指的是比赛场次，可以去[RM官网](https://www.robomaster.com/zh-CN/resource/video)，进入文件夹选择1个part。  
这是打开了62号🎦
![👊](https://github.com/V-9318/labelImg/raw/master/4.png)  
每个👨＆👩完成1个part即可，而后在confluence创建好的数据集采集页面标识:👴选择了哪个part避免重复，例如：
>张三 part1  

labelImg是一个能够自定义生成各种适用于yolo的数据集，也支持生成PascalVoc格式,下载链接：[hit](https://tzutalin.github.io/labelImg/)，尽量下载对应的最新版本，下载之后将data/predefined_classes.txt换成[predefined_classes.txt](https://share.weiyun.com/53noSDP)👉👉👉**这里要注意一下，名字不能修改**  
文件树🌳:  
windows_v1.8.0  
├── data  
│   └── predefined_classes.txt  
└── labelImg.exe  
  
linux_v1.4.3  
├── data  
│   └── predefined_classes.txt  
└── labelImg  

也可以在QQ群直接下载  

# 🧘‍windows&linux

打开labelImage，点击一下.exe或者.elf有👋就行。

1. 首先点击open_dir打开分发的数据集👊：  
![👊](https://github.com/V-9318/labelImg/raw/master/5.png)
![👊](https://github.com/V-9318/labelImg/raw/master/6.png)
2. 然后点击CreateRectBox，框出其中的车，并且选择车对应的车种，需要从下列的：  
    * infantry--步兵🏎
    * hero--英雄🚙
    * drone--无人机🚁
    * rune--工程🚎
    * sentry--哨兵🕋
双击某一项：  
![👊](https://github.com/V-9318/labelImg/raw/master/7.png)
3. 选择好了之后选择Verify Image然后保存成与图片同名的xml（**一定要同名！！，默认就是同名**），没有也不管，直接保存👊，就可以点击Next Image下一张了，如果对上次结果不满意可以选择Prev Image回到上一张进行修改，可以拖拉框也可以删除框重新创建。  
![👊](https://github.com/V-9318/labelImg/raw/master/8.png)  
![👊](https://github.com/V-9318/labelImg/raw/master/9.png)  
4. 弄完了是这样，所有的图片都有对应的xml在相同的📂下就行：  
![👊](https://github.com/V-9318/labelImg/raw/master/10.png)  
5. 没有  
6. 👇  
![👊](https://github.com/V-9318/labelImg/raw/master/3.gif)
