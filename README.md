# mpvue仿网易严选

# 前言 #
一直打算自己写接口,写一个上线的小程序,数据方面总是无从下手，无意中发现一个网友爬取的网易严选商城的一些数据大概一共有20张左右的表,算是相当详细了(对其中部分表的字段和部分数据进行了修改,)平时写项目大部分用的vue,所以直接选择了mpvue开发,后端一开始打算用php但是学了半个月感觉需要学的东西太多,短时间里写不出这个线上小程序,最后决定用node来开发提供接口。
# 技术站 #
前端：小程序、mpvue、async、await

后端：Node、koa2、mysql、knex.js操作数据库,可视化工具使用的Navicat
# 目前上线状态 #
由于域名备案小程序暂时无法上线,但是**小程序的服务端已经上线,接口都是访问的线上接口**,你只需要把源码克隆到本地,**直接在微信开发者工具中,就能请求到数据,看到效果** ,备案通过后会把二维码添加进来

# 喜欢的希望大家点个star鼓励一下,谢谢大家的支持!!!! #

# 商城主要实现的功能 #

- 首页、专题、分类、购物车、我的
- 小程序授权登陆获取用户信息
- 首页包含品牌制造页、品牌制造详情页面、新品首发页面、人气推荐页面、各分类列表
- 商品详情页面，包含常见问题、大家都在看商品列表、加入购物车、收藏商品、立即购买、下订单、选择收货地址
- 搜索功能，包含历史记录、热门搜索、搜索后列表展示、模糊搜索提示
- 商品列表部分包含综合、价格高低进行排序
- 专题功能，包含专题详情、专题推荐列表
- 分类，包含左边大分类和右边详细分类
- 购物车，包含商品单选全选、左滑删除商品、下订单等功能
- 地址管理，包含新建地址和导入微信地址，地址编辑、左滑删除、设置默认地址
- 我的页，包含我的收藏、地址管理、意见反馈

# 部分效果展示 #
### 1.首页展示和专题页效果
![](https://user-gold-cdn.xitu.io/2018/8/27/165793588dd8808f?w=323&h=571&f=gif&s=3649872)
![](https://user-gold-cdn.xitu.io/2018/8/25/165717735a9e3c60?w=327&h=573&f=gif&s=3983502)
### 2、分类页面，分类子页面以及搜索功能、搜索列表、历史记录、模糊搜索提示
![](https://user-gold-cdn.xitu.io/2018/8/25/1657185090f5d3cd?w=327&h=573&f=gif&s=884918)
![](https://user-gold-cdn.xitu.io/2018/8/25/1657188bf2746d85?w=327&h=573&f=gif&s=585295)
### 3、购物车功能添加购物车,单选多选,删除和商品收藏功能
![](https://user-gold-cdn.xitu.io/2018/8/25/165719656d9bdb5b?w=327&h=573&f=gif&s=1979300)
![](https://user-gold-cdn.xitu.io/2018/8/25/165719e76bd00f05?w=327&h=573&f=gif&s=1770550)
### 4、地址管理
![](https://user-gold-cdn.xitu.io/2018/8/25/165719e2d9b28ee1?w=327&h=573&f=gif&s=611343)

# 小程序后端送门 [点击进入小程序服务端地址](https://github.com/heyushuo/mpvue-shop)
# 项目总结和遇到的一些问题 # [点击进入博客查看详情](https://juejin.im/post/5b6323baf265da0f5511533a)
# 最后 #
- 喜欢的记得点个star,鼓励一下谢谢哈!!
- 微信号 hys838723
- qq群号 647099996