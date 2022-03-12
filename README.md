# Vue实战微信读书 开发企业级移动Web书城

> 作者：sam

## 课程地址

本课程为[慕课网](https://www.imooc.com)的实战课程，点击[这里](https://coding.imooc.com/class/285.html)进行学习，本教程主要用于辅助大家更快地上手项目，进入实战开发。

## 开发手册（持续更新中）
重点介绍如何搭建开发环境，如何进行阅读器开发
- [QA](doc/qa/QA.md) - 常见问题集
- [Chapter1](doc/chapter1/Chapter1.md) - 运行完整的源代码
- Chapter2 - 准备开发环境

## 知识汇总（敬请期待）
详细介绍课程中涉及的知识点，方便大家在实际工作中快速进行应用

## 说明
### 关于源码
本课程提供三份源码，分别为：随视频更新的源码、完整源码和免费课源码
- 跟随视频更新学习的同学点击[这里](https://git.imooc.com/coding-285/vue-imooc-ebook-chapter.git)获取源码，该源码与视频更新进度保持同步，方便大家对照学习
- 想直接获取完整源码的同学点击[这里](https://git.imooc.com/coding-285/vue-imooc-ebook.git)，该源码会不断完善和优化，保持持续更新
- 本课程开发过程中，需要用到免费课源码，点击[这里](https://git.imooc.com/coding-285/vue-imooc-ebook-free.git)获取

### 关于资源包
资源包使用说明：
- 搭建本地的运行环境需要下载资源包，资源包容量较大，所以存储到百度网盘中，大家可以点击[这里](https://pan.baidu.com/s/1x2N7vl8nd2x6x7FnlQH3Cg)进行下载，提取码: ksjv
- 大家也可以直接使用线上系统的资源包，这样可以省去搭建静态资源服务器的环节，具体的配置方法见[Chapter1](doc/chapter1/Chapter1.md)会详细说明

### 关于开发工具
本课程使用的开发工具是WebStorm，官方下载地址点击[这里](https://www.jetbrains.com/webstorm/download)
有兴趣的童鞋可以共同参与开发，可以添加我的微信号：wx406151651，QQ：406151651共同参与开发讨论。谢谢合作！！！

### 启动项目

```bash
# - windows
# install nvm
choco install nvm
# 下载对应的 node 版本
nvm install 14.0.0
nvm use 14.0.0
# 设置环境变量
set SASS_BINARY_SITE=https://npm.taobao.org/mirrors/node-sass/
# 下载 nrm cnpm
npm i nrm -g
npm i cnpm -g
# 切换到淘宝源
nrm use taobao
# 下载相关依赖
cnpm i
# 测试环境启动
npm run dev
```
