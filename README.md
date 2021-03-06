# 个人简历

##  基本信息
| | |
|-|-|
|姓名|张文安|
|民族|汉族|
|性别|男|
|籍贯|浙江温州|
|出生年月 | 1988.10|
|毕业院校 | 浙江理工大学(本科/通信工程)|
|毕业时间 | 2010年7月|
|联系电话 | 13588956978|
|邮箱 | jquerytech@gmail.com|
|求职方向 | 前端开发工程师|

## 自我简介
本人从2010年大学毕业后，就一直从事前端开发工作。

参与多个项目，涉及PC、H5，技术栈也较为广泛，包括早期的jquery、zepto、bootstrap，以及近期的react.js、vue.js等。主要采用webpack工具进行代码打包和编译。

目前在卖好车前端团队作为团队leader,从最初的1个前端,到最多30个前端,经历团队的整个发展过程。

在公司业务发展的过程中，也进行过微信小程序的开发以及React Native的尝试。

目前,公司绝大部分项目的技术栈已经转向到React.js以及Ant Design。

## 主要技能
前端基本技能就不罗列了。
近期主要使用的 React.js 以及 Ant Design，另外，也有部分项目使用vue.js。

## 工作经历
|时间|公司|
|-|-|
|2015-2019|杭州一骑轻尘信息技术有限公司|
|2012-2014|杭州般豆网络科技有限公司|
|2010-2012|杭州杰杰科技有限公司|

### 项目经历概要
|时间|描述|
|-|-|
|2017.5-至今|卖好车整个供应链上的各个产品,主要为手机端的H5页面,使用React.js与Ant Design。<br/>配合汽车金融信息服务,使用React.js与Ant Design开发了相关的H5页面, 来支持各流程功能<br/>配合汽车物流的验车环节,开发了相关的微信小程序<br/>配合各个后台管理系统的需要,使用Ant Design Pro开发了各个后台管理系统<br/>配合汽车仓储环节,开发了相关的库位图展示,涉及svg、d3.js、canvas等相关的技术|
|2016.2-2017.5 |卖好车的开发( b.maihaoche.com )期间公司从C端向B端转型,<br/>此时主要的技术栈也开始向React.js转型，涉及项目大多是手机端H5页面。|
|2015.1-2016.2 |买好车网站 (www.maihaoche.com , 目前已下线) 的开发。<br/>在买好车工作期间，主导整个网站项目的开发，包括PC端和手机端。涉及jquery、zepto的应用|

## 自我总结
在卖好车工作期间, 获益良多, 并做了以下总结:

### 代码管理及编译打包
*   团队人数增长的时候, 对Git的使用作了规范和总结, 使用了[Git Flow](https://github.com/zhangwenan/front-end-skills/blob/master/git/git-flow.md)的分支管理方式
*   代码规范( https://github.com/AlloyTeam/CodeGuide )
*   为了更好的约束代码规范，引入了 TypeScript、tslint/eslint
*   优化webpack打包速度。(早期短暂使用过grunt/gulp/fis等打包工具)

### 部署与调试
*   早期，没做前后端分离，在java项目中直接部署。后期，逐步引入*Docker*来进行打包编译。相应的,为所有前端项目添加了Dockerfile文件。另外，部署的机器，也从单个服务在线升级到多个服务在线，由负载均衡分发请求。
*   早期，全站使用的http，后来发现前端代码被劫持，就建议公司购买了相应的证书,全站使用了https
*   使用express.js 自行开发了一套前端发布系统，主要管理各个前端应用的静态资源版本、回滚、发布记录等。
*   为了进行更好的持续集成，引入jenkins来管理项目的发布。
*   为了方便数据mock，使用了三方开源的yapi，来管理接口

### 静态资源的管理
*   项目所有静态资源，使用的第三方的七牛CDN，开发了七牛的上传工具
*   三方库的查询系统。(https://github.com/zhangwenan/cdn)
*   内网搭建了公司的npm包管理系统，使用的是阿里的npmjs

### 安全相关
*   公司内部为了加强安全,需要对所有后台页面加上水印。又开发了相应的公共组件。(https://github.com/zhangwenan/watermark)
*   当业务发展到一定阶段的时候，发现了前端页面的一些XSS漏洞等问题，并做相应的解决。

### 其他
*   为了尽早发现项目中的前端代码错误，引入了sentry来监控js代码报错
