## 目标

基于Chaquopy写了个插件，集成到TVBoxOSC项目中，就可以愉快的使用Python来写爬虫逻辑了

### 免责声明
本项目仅供爬虫技术学习交流使用，所有代码开源且免费，严禁任何商业用途，搜索结果均来自源站，本人不承担任何责任

### 食用方法

#### 一定要开启存储权限！一定要开启存储权限！一定要开启存储权限！

#### 在线配置
###### 1. 安装apk (测试阶段只提供armeabi-v7a和x86_64)
###### 2. 使用在线配置文件(https://raw.githubusercontent.com/UndCover/PyramidStore/main/py.json)

#### 离线配置
###### 1. 安装apk
###### 2. 将plugin放到设备根目录
###### 3. 使用离线配置文件(https://raw.githubusercontent.com/UndCover/PyramidStore/main/local.json)

### 爬虫写法参考
https://github.com/UndCover/PyramidStore/blob/main/spider.md

### 其他版本可参考添加教程
https://github.com/UndCover/PyramidStore/blob/main/tutorial.md

### FAQ
###### 0. APP版本
使用TVBoxOSC最后一版代码，无其他添加

###### 1. 为什么会有这个东西
个人觉得python调试和维护起来会比较方便一点

###### 2.为什么现在放出来
Chaquopy在7月24日解除了license限制，然后就想放出来试试

###### 3.为什么apk会这么大
apk打包了armeabi-v7a和x86_64两个版本的依赖文件，所以比普通的版本大16m左右。后续会做优化

###### 4.会不会开源
未来代码将会出现在这里(https://github.com/UndCover/Pyramid)

###### 5.目前还有哪些问题
现缺失解密部分内容，以及解析器等功能

#### 问题反馈
有什么问题可以反馈到telegram(https://t.me/+A3SLQRmPVi9kOThl)
不过由于工作原因，可能不会很及时的处理问题，请耐心等待。