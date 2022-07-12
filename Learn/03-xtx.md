--- 
title: Project
---

<ArticleTopAd></ArticleTopAd>


## 01-电商
<!-- xtx_pc_client -->
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- meta:desc -->
    <meta name="description" content="小兔鲜儿官网，致力于打造全球最大的食品、生鲜电商购物平台">
    <!-- meta:kw -->
    <meta name="keywords" content="小兔鲜儿,食品,生鲜,服装,家电,电商,购物">
    <title>小兔鲜儿-新鲜、惠民、快捷！</title>
    <!-- link:favicon -->
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <!-- 按顺序引入：外链式样式表后写的生效 -->
    <link rel="stylesheet" href="./css/base.css">
    <link rel="stylesheet" href="./css/common.css">
    <link rel="stylesheet" href="./css/index.css">
</head>

<body>
    <!-- 快捷导航 -->
    <div class="shortcut">
        <div class="wrapper">
            <ul>
                <li><a href="#">请先登录</a></li>
                <li><a href="#">免费注册</a></li>
                <li><a href="#">我的订单</a></li>
                <li><a href="#">会员中心</a></li>
                <li><a href="#">帮助中心</a></li>
                <li><a href="#">在线客服</a></li>
                <li><a href="#"><span></span>手机版</a></li>
            </ul>
        </div>
    </div>

    <!-- 头部 -->
    <div class="header wrapper">
        <div class="logo">
            <h1><a href="#">小兔鲜儿</a></h1>
        </div>
        <div class="nav">
            <ul>
                <li><a href="#">首页</a></li>
                <li><a href="#">生鲜</a></li>
                <li><a href="#">美食</a></li>
                <li><a href="#">餐厨</a></li>
                <li><a href="#">电器</a></li>
                <li><a href="#">居家</a></li>
                <li><a href="#">洗护</a></li>
                <li><a href="#">孕婴</a></li>
                <li><a href="#">服装</a></li>
            </ul>
        </div>
        <div class="search">
            <input type="text" placeholder="搜一搜">
            <!-- 定位 放大镜 -->
            <span></span>
        </div>
        <div class="car">
            <span>2</span>
        </div>
    </div>

    <!-- banner -->
    <div class="banner">
        <div class="wrapper">
            <!-- 有多少个图,就有多少个li -->
            <ul>
                <li><a href="#"><img src="./uploads/banner_1.png" alt=""></a></li>
            </ul>

            <!-- 侧导航 -->
            <div class="aside">
                <ul>
                    <li><a href="#">生鲜<span>水果 蔬菜</span></a></li>
                    <li><a href="#">生鲜<span>水果 蔬菜</span></a></li>
                    <li><a href="#">生鲜<span>水果 蔬菜</span></a></li>
                    <li><a href="#">生鲜<span>水果 蔬菜</span></a></li>
                    <li><a href="#">生鲜<span>水果 蔬菜</span></a></li>
                    <li><a href="#">生鲜<span>水果 蔬菜</span></a></li>
                    <li><a href="#">生鲜<span>水果 蔬菜</span></a></li>
                    <li><a href="#">生鲜<span>水果 蔬菜</span></a></li>
                    <li><a href="#">生鲜<span>水果 蔬菜</span></a></li>
                    <li><a href="#">生鲜<span>水果 蔬菜</span></a></li>
                </ul>
            </div>

            <!-- 箭头 -->
            <!-- prev：上一个 -->
            <a href="#" class="prev"></a>
            <!-- next：下一个 -->
            <a href="#" class="next"></a>

            <!-- 圆点：当前状态：current / active -->
            <!-- js 找到用户点击的li 添加类名 li变成白色的 -->
            <ol>
                <li></li>
                <li></li>
                <li class="current"></li>
                <li></li>
                <li></li>
            </ol>
        </div>
    </div>

    <!-- 新鲜好物 -->
    <div class="goods wrapper">
        <!-- hd header 头部 -->
        <div class="hd">
            <h2>新鲜好物<span>新鲜出炉 品质靠谱</span></h2>
            <a href="#">查看全部</a>
        </div>
        <!-- body 身体, 内容 -->
        <div class="bd clearfix">
            <ul>
                <li>
                    <a href="#">
                        <img src="./uploads/new_goods_1.jpg" alt="">
                        <h3>睿米无线吸尘器F8</h3>
                        <div>￥<span>899</span></div>
                        <b>新品</b>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./uploads/new_goods_1.jpg" alt="">
                        <h3>睿米无线吸尘器F8</h3>
                        <div>￥<span>899</span></div>
                        <b>新品</b>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./uploads/new_goods_1.jpg" alt="">
                        <h3>睿米无线吸尘器F8</h3>
                        <div>￥<span>899</span></div>
                        <b>新品</b>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./uploads/new_goods_1.jpg" alt="">
                        <h3>睿米无线吸尘器F8</h3>
                        <div>￥<span>899</span></div>
                        <b>新品</b>
                    </a>
                </li>
            </ul>
        </div>
    </div>

    <!-- 生鲜 -->
    <div class="shengxian wrapper">
        <div class="hd">
            <h2>生鲜</h2>
            <a href="#" class="more">查看全部</a>
            <ul>
                <li><a href="#">水果</a></li>
                <li><a href="#">水果</a></li>
                <li><a href="#">水果</a></li>
                <li><a href="#">水果</a></li>
                <li><a href="#">水果</a></li>
                <li><a href="#">水果</a></li>
                <li><a href="#">水果</a></li>
            </ul>
        </div>
        <div class="bd clearfix">
            <div class="left">
                <a href="#"><img src="./uploads/fresh_goods_cover.png" alt=""></a>
            </div>
            <div class="right">
            </div>
        </div>
    </div>
    <!-- 版权区域 -->
    <div class="footer">
        <div class="wrapper">
            <div class="top">
                <ul>
                    <li>
                        <!-- 通过伪元素添加标签实现精灵图 -->
                        <span>价格亲民</span>
                    </li>
                    <li>
                        <span>物流快捷</span>
                    </li>
                    <li>
                        <span>品质新鲜</span>
                    </li>
                </ul>
            </div>
            <div class="bottom">
                <p>
                    <a href="#">关于我们</a>
                    <a href="#">帮助中心</a>
                    <a href="#">售后服务</a>
                    <a href="#">配送与验收</a>
                    <a href="#">商务合作</a>
                    <a href="#">搜索推荐</a>
                    <a href="#">友情链接</a>
                </p>
                <p>CopyRight @ 小兔鲜儿</p>
            </div>
        </div>
    </div>
</body>

</html>
```

<!-- index.css -->
```css
/* 放index页面的样式表 */
/* banner */
.banner {
    height: 500px;
    background-color: #f5f5f5;
}

.banner .wrapper {
    position: relative;
    height: 500px;
    background-color: pink;
}

/* 侧导航 */
.banner .aside {
    position: absolute;
    left: 0;
    top: 0;
    width: 250px;
    height: 500px;
    background-color: rgba(0,0,0,.8);
}

.banner .aside li {
    height: 50px;
    line-height: 50px;
}

.banner .aside a {
    position: relative;
    /* 宽度和父级一样 */
    padding-left: 36px;
    padding-right: 19px;
    display: block;
    height: 50px;

    color: #fff;
}

.banner .aside a span {
    margin-left: 15px;
    font-size: 14px;
}

.banner .aside a:hover {
    background-color: #27ba9b;
}

/* a的里面最后的位置添加箭头 */
.banner .aside a::after {
    position: absolute;
    right: 19px;
    top: 19px;
    content: '';
    width: 6px;
    height: 11px;
    background-image: url(../images/sprites.png);
    background-position: -80px -110px;
}

/* 箭头 */
.next,
.prev {
    position: absolute;
    top: 228px;
    width: 45px;
    height: 45px;
    background-color: rgba(0,0,0,.2);
    background-image: url(../images/sprites.png);
    border-radius: 50%;
}

/* 背景图位置负责2件事: 改变箭头在盒子里面的位置; 改变精灵图的位置 */
/* 导致在精灵图中测量的尺寸不准确 */
/* 解决方案有2种: 
    1. 书写背景图位置属性, 借助谷歌的调试工具调试具体的位置数值
    2. 书写标签的时候, a负责盒子,里面再添加一个span负责箭头
*/
.prev {
    left: 260px;
    background-position: 14px -60px;
}

.next {
    right: 10px;
    background-position: -23px -60px;
}

/* 圆点 */
.banner ol {
    position: absolute;
    left: 680px;
    bottom: 30px;

    height: 10px;
}

.banner ol li {
    float: left;
    margin-right: 24px;
    width: 10px;
    height: 10px;
    background-color: rgba(255, 255, 255, 0.4);
    border-radius: 50%;
    cursor: pointer;
}

.banner ol .current {
    background-color: #fff;
}

/* 新鲜好物 */

.goods .hd {
    height: 114px;
    line-height: 114px;
}

.goods .hd h2 {
    float: left;
    font-size: 29px;
    font-weight: 400;

    height: 114px;
}

.goods .hd h2 span {
    margin-left: 34px;
    font-size: 16px;
    color: #999;
}

.goods .hd a,
.shengxian .hd .more {
    float: right;
    color: #999;
}

.goods .hd a::after,
.shengxian .hd .more::after {
    content: '';
    display: inline-block;
    margin-left: 13px;
    width: 7px;
    height: 13px;
    background-image: url(../images/sprites.png);
    background-position: 0 -110px;
    vertical-align: middle;
}

.goods .bd li {
    position: relative;
    float: left;
    margin-right: 8px;
    width: 304px;
    height: 405px;
    background-color: #f0f9f4;
    text-align: center;
}

.goods .bd li:last-child {
    margin-right: 0;
}

.goods .bd li img {
    width: 304px;
}

.goods .bd li h3 {
    margin-top: 20px;
    margin-bottom: 10px;
    font-size: 20px;
    font-weight: 400;
}

.goods .bd li div {
    color: #9a2e1f;
    font-size: 17px;
}

.goods .bd li div span {
    font-size: 23px;
}

.goods .bd li b {
    position: absolute;
    left: 17px;
    top:18px;
    width: 28px;
    height: 51px;
    border: 1px solid #27ba9b;
    border-radius: 2px;
    font-size: 18px;
    color: #27ba9b;
    font-weight: 400;
    line-height: 24px;
}

/* 生鲜 */
.shengxian .hd {
    height: 96px;
    line-height: 96px;
}

.shengxian .hd h2 {
    float: left;
    font-size: 29px;
    font-weight: 400;
}

.shengxian .hd .more {
    float: right;
}

.shengxian .hd ul {
    float: right;
    margin-right: 65px;
}

.shengxian .hd ul li {
    float: left;
}

.shengxian .hd li a {
    padding: 2px 7px;
    margin-left: 6px;
}

.shengxian .hd li a:hover {
    background-color: #27ba9b;
    color: #fff;
}

.shengxian .bd .left {
    float: left;
    width: 240px;
    height: 610px;
    background-color: pink;
}

.shengxian .bd .right {
    float: left;
    width: 1000px;
    height: 610px;
    background-color: skyblue;
}
```
<!-- base.css -->
```css
/* 清除默认样式的代码 */
/* 去除常见标签默认的 margin 和 padding */
body,
h1,
h2,
h3,
h4,
h5,
h6,
p,
ul,
ol,
li,
dl,
dt,
dd,
input {
  margin: 0;
  padding: 0;
}

/* 內减模式 */
* {
    box-sizing: border-box;
}

/* 设置网页统一的字体大小、行高、字体系列相关属性 */
body {
  font: 16px/1.5 "Helvetica Neue", Helvetica, Arial, "Microsoft Yahei",
    "Hiragino Sans GB", "Heiti SC", "WenQuanYi Micro Hei", sans-serif;
  color: #333;
}

/* 去除列表默认样式 */
ul,
ol {
  list-style: none;
}

/* 去除默认的倾斜效果 */
em,
i {
  font-style: normal;
}

/* 去除a标签默认下划线，并设置默认文字颜色 */
a {
  text-decoration: none;
  color: #333;
}

/* 设置img的垂直对齐方式为居中对齐，去除img默认下间隙 */
img {
  vertical-align: middle;
}

/* 去除input默认样式 */
input {
  border: none;
  outline: none;
  color: #333;
}

/* 左浮动 */
.fl {
  float: left;
}

/* 右浮动 */
.fr {
  float: right;
}

/* 双伪元素清除法 */
.clearfix::before,
.clearfix::after {
  content: "";
  display: table;
}
.clearfix::after {
  clear: both;
}
```
<!-- common.css -->
```css
/* 各个页面相同的样式表 : 头, 尾部 */
/* 版心 */
.wrapper {
    width: 1240px;
    margin: 0 auto;
}

/* 快捷导航 */
.shortcut {
    height: 52px;
    background-color: #333;
}

.shortcut .wrapper {
    height: 52px;
}

/* 目的: 所有的文字内容居右侧对齐 */
.shortcut .wrapper ul {
    float: right;
}

/* 目的: 让所有的文字在一行显示 */
.shortcut .wrapper li {
    float: left;
    line-height: 52px;
}

.shortcut .wrapper a {
    padding: 0 16px;
    border-right: 1px solid #666;
    font-size: 14px;
    color: #dcdcdc;
}

.shortcut .wrapper a span {
    display: inline-block;
    margin-right: 8px;
    width: 11px;
    height: 16px;
    background-image: url(../images/sprites.png);
    background-position: -160px -70px;

    vertical-align: middle;
}

/* 清除a的边框线: 最后一个li里面的a */
.shortcut .wrapper li:last-child a {
    border: 0;
}

/* 头部 */
.header {
    margin: 30px auto;
    height: 70px;
}

.logo {
    float: left;
    width: 207px;
    height: 70px;
}

/* logo 搜索引擎优化做法 */
.logo h1 {
    width: 207px;
    height: 70px;
}

.logo h1 a {
    display: block;
    width: 207px;
    height: 70px;
    background-image: url(../images/logo.png);
    background-size: contain;
    /* 目的: 让h1里面的字看不见 */
    font-size: 0;
}

.nav {
    float: left;
    margin-left: 40px;
    height: 70px;
}

.nav li {
    float: left;
    margin-right: 48px;
    line-height: 70px;
}

.nav li a {
    padding-bottom: 7px;
}


.nav li a:hover {
    color: #27ba9b;
    border-bottom: 1px solid #27ba9b;
}

.search {
    position: relative;
    float: left;
    margin-top: 24px;
    margin-left: 34px;
    width: 172px;
    height: 30px;
    border-bottom: 2px solid #e7e7e7;
}

.search input {
    padding-left: 30px;
    width: 172px;
    height: 28px;
}

.search input::placeholder {
    font-size: 14px;
    color: #ccc;
}

.search span {
    position: absolute;
    left: 2px;
    top: 0;
    /* display: inline-block; */
    width: 18px;
    height: 18px;
    background-image: url(../images/sprites.png);
    background-position: -79px -69px;
}

.car {
    position: relative;
    float: left;
    margin-top: 28px;
    margin-left: 15px;
    width: 23px;
    height: 23px;
    background-image: url(../images/sprites.png);
    background-position: -119px -69px;
}

.car span {
    /* 绝对定位, 盒子具备行内块特点 */
    position: absolute;
    right: -13px;
    top: -6px;
    width: 20px;
    height: 15px;
    background-color: #e26237;
    border-radius: 8px;

    font-size: 13px;
    color: #fff;
    text-align: center;
    line-height: 15px;
}

/* 版权footer */
.footer {
    height: 342px;
    background-color: #333;
}

.footer .wrapper {
    width: 1393px;
}

.footer .top {
    padding-top: 59px;
    padding-left: 135px;
    height: 175px;
    border-bottom: 3px solid #434343;
}

.footer .top li {
    position: relative;
    float: left;
    margin-right: 300px;
    width: 195px;
    height: 58px;

    line-height: 58px;
}

.footer .top li:last-child {
    margin-right: 0;
}

/* 伪元素添加的标签  行内 */
/* 如果行内块和行内文字无法通过vertical-align或行高对齐, 定位 */
.footer .top li::before {
    position: absolute;
    left: 0;
    top: 0;
    /* display: inline-block; */
    content: '';
    width: 58px;
    height: 58px;
    background-image: url(../images/sprites.png);
    vertical-align: middle;
}

.footer .top li span {
    margin-left: 77px;
    font-size: 28px;
    color: #fff;
}

/* 第二个li里面的berfore添加背景图位置属性 */
.footer .top li:nth-child(2)::before {
    background-position: -130px 0;
}
.footer .top li:nth-child(3)::before {
    background-position: -64px 0;
}

.footer .bottom {
    padding-top: 40px;
    font-size: 14px;
    color: #999;
    text-align: center;
}

.footer .bottom a {
    font-size: 14px;
    color: #999;
}

.footer .bottom p {
    margin-bottom: 20px;
}
```
