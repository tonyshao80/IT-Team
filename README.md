# IT-Team

# 前言：
> 正君餐饮总公司IT部项目版本控制说明，由团队成员更新和维护。

# 概述
> 针对某个平台开发产品请选择对应平台UI，如微信公众号或者小程序开发则选择[WeUI](https://github.com/weui/weui)。[微信资源(SDK,开发工具等)](https://github.com/muwubbq/WeChat)
，钉钉则选择[钉钉UI](https://github.com/amazeui/amazeui-dingtalk)与[DingTalk-SDK](https://github.com/muwubbq/DingTalk)。自由平台，则选择[amazeui](https://github.com/amazeui/amazeui)。配合[amazeui代码片段](https://github.com/amazeui/snippets)开发速度会有一个大大提升，推荐。

## 团队协作工具
- [倍洽bearychat](https://muwuit.bearychat.com)（沟通）

- [看板工具Trello](https://trello.com/itteam461)（项目进度，需求）

- [ProcessOn在线作图](http://www.processon.com)（流程图，逻辑图）

- IDE与编辑器，选一个自己顺手的就行，尽量统一。（sublime text居多。）

## 已开发完并正在维护的项目

## [木屋烧烤](https://github.com/muwubbq)

## 移动端UI库

1. [微信开发WeUI](https://github.com/weui/weui)

2. [钉钉UI](https://github.com/amazeui/amazeui-dingtalk)

3. [阿里巴巴UED团队的SUI-Mobile](https://github.com/sdc-alibaba/SUI-Mobile)

## PC端前端框架

1. [amazeui](https://github.com/amazeui/amazeui)

2. [网易的NEC（CSS解决方案）](http://nec.netease.com/)


## 库/框架|构建工具|包管理器
1. [angular.js](http://angularjs.org)/[react](https://facebook.github.io/react/) /[vue](http://vuejs.org/)/[backbone](http://backbonejs.org/)/[node.js](https://nodejs.org/en/)

2. [gulp](http://gulpjs.com/)/[grunt](http://gruntjs.com/)/[yeoman](http://yeoman.io/)/[webpack](https://webpack.github.io/)

3. [yarn](https://yarnpkg.com/)/[bower](https://bower.io/)/[npm](https://www.npmjs.com/) /[node-browserify](http://browserify.org/)

...


### 前端代码规范

前端部分严格按照[腾讯 AlloyTeam团队](http://alloyteam.github.io/CodeGuide/)
前端框架不限制，但是一定要简洁，简约，易维护性为出发点。
避免代码混乱，冗余。

## 团队成员要求

1. 为什么需要有团队代码规范？
虽然这些细节是小事，不会有体验或者性能上的优化，但是却体现了一个coder和团队的专业程度 
所以不管团队有多少人，代码风格都应该师出同门！

2. 如何使用？
在使用之前花一点时间把规范看一遍是很必要的，
然后按照这里的步骤配置好编辑器和构建检查（目前仅提供了sublime3和grunt的配置）

主要使用到了jscs，jshint，sass-lint，csslint 四个规范检查插件，
JsFormat（它其实用的是jsbeautifier），CSScomb两个格式化的插件，
使用其他编辑器的话可以自己去搜一下相关的这些插件。


### 后端代码规范

后端语言暂时主流PHP.
听说PHP最好的编程语言没有之一，(别打我)...
不限制，如会python，Node,js，java，Ruby更好。

框架...

PHP代码规范
更新中...

[### 团队成员技能要求](https://github.com/muwubbq/IT-Team/blob/master/%E9%80%9A%E7%94%A8%E6%8A%80%E8%83%BD.md)

## 硬性知识储备

### 版本控制
Git/Github，必会。

1. 设置SSH Key
检查是否已经有SSH Key。  
$cd ~/.ssh
2. 如果没有则生成一个新的SSH。
$ssh-keygen -t rsa -C "email" 三次回车即可。
3. 把Key填写入自己Github。

Git与Github是完全不同的，这点要区别。如何不同google之。

会设置key仅仅只是开始，还没入门，继续深入[Git](https://github.com/TeamStuQ/skill-map/blob/master/data/map-Git.md)

（如果访问慢，被墙，你能直接解决掉吧？）。

版本控制熟练之后，技能树请继续参考对应方向。[StuQ 程序员技能图谱](https://github.com/TeamStuQ/skill-map)