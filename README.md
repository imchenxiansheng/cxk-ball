## h5小游戏—打砖块

本项目是利用原生js实现的h5小游戏，在实现时使用了大量es6语法，对于es6语法不太熟悉的小伙伴可以先查阅相关资料了解一下

## 项目截图

![1](images/screenshot.png)

## 项目实现目标：
* 学习canvas相关api
* 看相关资料学习游戏设计流程，及游戏逻辑
* 使用es6语法进行项目重构，熟练使用es6语法

## 已完成功能：
- [x] 设计多个关卡
- [x] 显示计分板
- [x] 特殊砖块血量更多
- [x] 小球撞击挡板多角度反弹
- [x] 小球与砖块撞击不同部位，反弹角度不同

## 待优化功能：
- [ ] 小球与挡板和砖块之间的碰撞模型不够精确
- [ ] 图片素材有待更新

**demo**：[线上地址](https://yangyunhe369.github.io/h5-game-blockBreaker/)

## 下载源码

```
git clone https://github.com/yangyunhe369/h5-game-blockBreaker.git
```

## 目录结构

```
.
├─ index.html                   // 首页html
│  
├─ css                          // css样式资源文件
├─ images                       // 图片资源文件  
└─ js
   ├─ common.js                 // 公共js方法
   ├─ game.js                   // 游戏主要运行逻辑
   └─ scene.js                  // 游戏场景相关类
```

>common.js => 引入公共方法
>scene.js => 引入游戏场景素材相关原型，包括砖块、小球、挡板、生成的砖块对象集合、计分板
>game.js => 引入游戏引擎
>main.js => 游戏运行主函数

## 说明

如果对您有帮助，您可以点右上角 "Star" 支持一下 谢谢！ ^_^

或者您可以 "follow" 一下，我会不断开源更多的有趣的项目

## 个人简介

作者：弦云孤赫(David Yang)

职业：web前端开发工程师

爱好：网游、音乐（吉他）

## 联系方式

QQ：314786482

微信：yangyunhe_yyh

坐标：四川成都