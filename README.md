源自：https://github.com/GleasonBian/CornerstoneVueWADO
原工程无法正常显示dicom图片，因此做了以下修改：
1、添加自己的dicom文件于testImages中；
2、修改Helloworld.vue里面一个小错误；
3、添加static/Dicom.json；
4、把static/dist里面的cornerstoneWADOImageLoade等文件更新为2.2.4版本。

以下为原工程内容：

# CornerstoneVueWADO

> 一个基于 Cornerstone 解析并显示 Dicom 图像的 Vue 项目

## Build Setup

``` bash
# 安装依赖
npm install

* 以下依赖项  如果在 node_modules 目录中不存在 才需要 安装

# install cornerstone
npm install cornerstone-core --save

# install dicom-parser
npm install dicom-parser --save

# serve with hot reload at localhost:8080
npm run dev

```
# 使用方法

* 具体使用步骤 请看 HelloWorld.vue 文件
* 如需帮助请 发送邮件给我 Email: bianliuzhu@gmail.com
代码图片
![代码](https://github.com/GleasonBian/GithubReadmeImage/blob/master/code.jpg)

response(res):
![response](https://github.com/GleasonBian/GithubReadmeImage/blob/master/res.jpg)

![cornerstoneWADO_res.jpg](https://github.com/GleasonBian/GithubReadmeImage/blob/master/cornerstoneWADO_res.jpg)

![cornerstoneWADO_res.body.value.jpg](https://github.com/GleasonBian/GithubReadmeImage/blob/master/cornerstoneWADO_res.body.value.jpg)
