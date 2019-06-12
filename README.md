# cnode-project

## vue-cli脚手架一键搭建工程

1. 安装淘宝npm镜像

    ````
    npm install -g cnpm --registry=https://registry.npm.taobao.org
    ````

2. 全局安装 vue-cli 

    ````
    cnpm install -g vue-cli
    ````

3. 初始化项目
    ````
    vue init webpack my-project
    ````

4. 进入项目

    ````
    cd my-project
    ````

5. 安装依赖
    ````
    cnpm install 
    ````

6. 启动项目

    ````
    cnpm run dev 
    ````

    #### 组件
   ````

1. Header 头部
2. PostList 列表
3. Article 文章详情页
4. SlideBar 文章侧边栏
5. UserInfo 用户个人信息
6. Pagination 分页组件



   ````
#### Header 头部

#### PostList 列表

````
官网提供API接口: [链接](https://cnodejs.org/api/v1/topics)
列表数据: 

头像: author:avatar_url

回复量: reply_count

访问量: visit_count

标题: title

需要使用到过滤器:

时间: last_reply_at

帖子分类:

        是否置顶: top

        是否标注精华: good

        除置顶,精华外的分区: tab

                - 分享 share

                - 问答 ask

                - job 招聘

````



#### Article 组件

````
获取:

    API: https://cnodejs.org/api/v1/topic/ + 帖子ID

````
#### UserInfo 组件

````
获取:

    API: https://cnodejs.org/api/v1/user/ + username

````


