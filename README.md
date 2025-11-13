# 图书借阅推荐系统 python135

## 项目概述

本项目是基于Python开发的图书借阅推荐系统。系统采用了Django框架进行后端开发，并使用MySQL数据库进行数据存储。前端界面则通过Vue.js构建，实现了用户注册、登录、图书搜索、借阅、归还等核心功能。

## 技术栈

- 后端：Python + Django
- 前端：Vue.js
- 数据库：MySQL

## 功能模块

### 前台功能

- 首页
- 图书推荐
- 图书详情页
- 用户中心模块

### 后台功能

- 总览
- 借阅管理
- 图书管理
- 分类管理
- 标签管理
- 评论管理
- 用户管理
- 运营管理
- 日志管理
- 系统信息模块

## 系统角色

- 图书馆管理者
- 读者

## 运行环境

- 后端：Python 3.8+，Django 3.x，MySQL 5.x
- 前端：Vue.js 2.x，现代浏览器

## 目录结构

```
Project
├── backend               # 后端目录
│   ├── apps              # 应用目录
│   ├── manage.py         # 管理脚本
│   └── ...
└── frontend              # 前端目录
    ├── src               # 源码目录
    ├── public            # 公共资源
    ├── vue.config.js     # Vue配置文件
    └── ...
```

## 部署步骤

1. 安装后端依赖：`pip install -r requirements.txt`
2. 配置数据库：按照`settings.py`中的数据库配置进行设置
3. 前端编译：进入`frontend`目录，执行`npm install`后运行`npm run build`
4. 部署至Web服务器

## 核心亮点

- 分层架构设计：高内聚、低耦合，易于维护和扩展
- 推荐算法：基于用户行为数据的图书推荐，采用余弦相似度计算用户之间的相似度
- 安全可靠：经过全面的功能测试、性能测试、兼容性测试和安全性测试

## 用户-图书评分矩阵与推荐逻辑

用户-图书评分矩阵构建通过`build_user_item_matrix()`函数，根据用户行为设定评分。

- 收藏书籍评分：1
- 心愿书籍评分：0.5
- 其他书籍评分：0

利用余弦相似度计算用户之间的相似度，根据相似用户的行为推荐图书。

- 推荐逻辑：推荐与目标用户行为相似的其他用户所喜欢的书籍
- 推荐数量：最多12本
- 协同过滤：基于用户的协同过滤，推荐相似用户喜好的图书

## 清理声明

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img11.360buyimg.com/ddimg/jfs/t1/324996/1/23555/49075/68d2de1aF48410429/b13d0f3e7a858b78.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/341831/24/6813/45962/68d2de1aFa62b7dfe/c195780fe04bf211.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/351128/12/6702/25222/68d2de1bF2064704c/4013e499fe5e93d3.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/326339/31/23588/41945/68d2de1bFe84b8629/7b32b037dfc6f09a.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/328226/30/23057/27630/68d2de1bF6059a104/2032329f6e2da793.jpg)
