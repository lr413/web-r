--- 
title: Project
---

<ArticleTopAd></ArticleTopAd>


## 01-study
<!-- 学成在线 -->
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>学成在线</title>
    <link rel="stylesheet" href="./css/index.css">
</head>
<body>
    <!-- 网站的首页, 所有网站的首页都叫index.html, 因为服务器找首页都是找index.html -->
    <!-- 布局: 从外到内, 从上到下, 从左到右 -->
    <!-- CSS: 浮动/display ; 盒子模型; 文字样式 -->

    <!-- 头部header: 负责头部区域的样式, wrapper只负责版心效果 -->
    <div class="header wrapper">
        <h1>
            <a href="#"><img src="./images/logo.png" alt=""></a>
        </h1>

        <!-- 导航 -->
        <div class="nav">
            <ul>
                <li><a href="#">首页</a></li>
                <li><a href="#">课程</a></li>
                <li><a href="#">职业规划</a></li>
            </ul>
        </div>
        <!-- 搜索 -->
        <div class="search">
            <input type="text" placeholder="输入关键词"><button></button>
        </div>
        <!-- 用户 -->
        <div class="user">
            <img src="./images/user.png" alt="">
            <span>lilei</span>
        </div>
    </div>

    <!-- 轮播图banner -->
    <div class="banner">
        <div class="wrapper">
            <div class="left">
                <ul>
                    <li><a href="#">前端开发<span>></span></a></li>
                    <li><a href="#">前端开发<span>></span></a></li>
                    <li><a href="#">前端开发<span>></span></a></li>
                    <li><a href="#">前端开发<span>></span></a></li>
                    <li><a href="#">前端开发<span>></span></a></li>
                    <li><a href="#">前端开发<span>></span></a></li>
                    <li><a href="#">前端开发<span>></span></a></li>
                    <li><a href="#">前端开发<span>></span></a></li>
                    <li><a href="#">前端开发<span>></span></a></li>
                </ul>
            </div>
            <div class="right">
                <h2>我的课程表</h2>
                <div class="content">
                    <dl>
                        <dt>继续学习 程序语言设计</dt>
                        <dd>正在学习-使用对象</dd>
                    </dl>
                    <dl>
                        <dt>继续学习 程序语言设计</dt>
                        <dd>正在学习-使用对象</dd>
                    </dl>
                    <dl>
                        <dt>继续学习 程序语言设计</dt>
                        <dd>正在学习-使用对象</dd>
                    </dl>
                </div>
                <a href="#" class="more">全部课程</a>
            </div>
        </div>
    </div>

    <!-- 精品推荐 -->
    <div class="goods wrapper">
        <h2>精品推荐</h2>
        <ul>
            <li><a href="#">jQuery</a></li>
            <li><a href="#">jQuery</a></li>
            <li><a href="#">jQuery</a></li>
            <li><a href="#">jQuery</a></li>
            <li><a href="#">jQuery</a></li>
            <li><a href="#">jQuery</a></li>
        </ul>
        <a href="#" class="xingqu">修改兴趣</a>
    </div>

    <!-- 精品推荐课程 -->
    <div class="box wrapper">
        <div class="title">
            <h2>精品推荐</h2>
            <a href="#">查看全部</a>
        </div>

        <div class="content clearfix">
            <ul>
                <li>
                    <a href="#">
                        <img src="./images/course07.png" alt="">
                        <h3>Think PHP 5.0 博客系统实战项目演练</h3>
                        <p><span>高级</span>  •  1125人在学习</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./images/course07.png" alt="">
                        <h3>Think PHP 5.0 博客系统实战项目演练</h3>
                        <p><span>高级</span>  •  1125人在学习</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./images/course07.png" alt="">
                        <h3>Think PHP 5.0 博客系统实战项目演练</h3>
                        <p><span>高级</span>  •  1125人在学习</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./images/course07.png" alt="">
                        <h3>Think PHP 5.0 博客系统实战项目演练</h3>
                        <p><span>高级</span>  •  1125人在学习</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./images/course07.png" alt="">
                        <h3>Think PHP 5.0 博客系统实战项目演练</h3>
                        <p><span>高级</span>  •  1125人在学习</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./images/course07.png" alt="">
                        <h3>Think PHP 5.0 博客系统实战项目演练</h3>
                        <p><span>高级</span>  •  1125人在学习</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./images/course07.png" alt="">
                        <h3>Think PHP 5.0 博客系统实战项目演练</h3>
                        <p><span>高级</span>  •  1125人在学习</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./images/course07.png" alt="">
                        <h3>Think PHP 5.0 博客系统实战项目演练</h3>
                        <p><span>高级</span>  •  1125人在学习</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./images/course07.png" alt="">
                        <h3>Think PHP 5.0 博客系统实战项目演练</h3>
                        <p><span>高级</span>  •  1125人在学习</p>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="./images/course07.png" alt="">
                        <h3>Think PHP 5.0 博客系统实战项目演练</h3>
                        <p><span>高级</span>  •  1125人在学习</p>
                    </a>
                </li>
                
            </ul>
        </div>
    </div>

    <!-- 版权 : 注意要清除浮动的影响, 课程的li 的 父级 -->
    <!-- li都浮动了, 脱标, 撑不开父级的高度 -->
    <div class="footer">
        <div class="wrapper">
            <div class="left">
                <img src="./images/logo.png" alt="">
                <p>学成在线致力于普及中国最好的教育它与中国一流大学和机构合作提供在线课程。<br>
                    © 2017年XTCG Inc.保留所有权利。-沪ICP备15025210号</p>
                <a href="#">下载APP</a>
            </div>
            <div class="right">
                <dl>
                    <dt>合作伙伴</dt>
                    <dd><a href="#">合作机构</a></dd>
                    <dd><a href="#">合作导师</a></dd>
                </dl>
                <dl>
                    <dt>合作伙伴</dt>
                    <dd><a href="#">合作机构</a></dd>
                    <dd><a href="#">合作导师</a></dd>
                </dl>
                <dl>
                    <dt>合作伙伴</dt>
                    <dd><a href="#">合作机构</a></dd>
                    <dd><a href="#">合作导师</a></dd>
                </dl>
            </div>
        </div>
    </div>
</body>
</html>
```
<!-- index.css -->
```css
/* index.css是用来美化首页的 */
* {
    margin: 0;
    padding: 0;
    /* 內减模式 */
    box-sizing: border-box;
}

li {
    list-style: none;
}
a {
    text-decoration: none;
}

.clearfix:before,.clearfix:after {
    content:"";
    display:table; 
  }
  .clearfix:after {
    clear:both;
  }


body {
    background-color: #f3f5f7;
}

/* 版心 */
.wrapper {
    width: 1200px;
    margin: 0 auto;
}

/* 头部 */
.header {
    height: 42px;
    /* margin-top: 30px;
    margin-bottom: 30px; */
    margin: 30px auto;
}

h1 {
    float: left;
}

/* 导航 */
.nav {
    float: left;
    margin-left: 70px;
    height: 42px;
}

.nav li {
    float: left;
    margin-right: 26px;
}

.nav li a {
    display: block;
    padding: 0 9px;
    height: 42px;
    line-height: 42px;
    /* border-bottom: 2px solid #00a4ff; */

    font-size: 18px;
    color: #050505;
}

.nav li a:hover {
    border-bottom: 2px solid #00a4ff;
}

/* 搜索 */
.search {
    float: left;
    margin-left: 59px;
    width: 412px;
    height: 40px;
    border: 1px solid #00a4ff;
}

.search input {
    float: left;
    padding-left: 20px;
    /* 左右加一起的尺寸要小于等于410 */
    width: 360px;
    height: 38px;
    border: 0;
}

/* 控制placeholder的样式 */
.search input::placeholder {
    font-size: 14px;
    color: #bfbfbf;
}

.search button {
    float: left;
    width: 50px;
    height: 40px;
    background-image: url(../images/btn.png);
    border: 0;
}

.user {
    float: right;
    margin-right: 35px;
    height: 42px;
    line-height: 42px;
}
.user img {
    /* 调节图片垂直对齐方式, middle:居中 */
    vertical-align: middle;
}

/* 轮播图 */
.banner {
    height: 420px;
    background-color: #1c036c;
}

.banner .wrapper {
    height: 420px;
    background-image: url(../images/banner2.png);
}

.banner .left {
    float: left;

    padding: 0 20px;

    width: 190px;
    height: 420px;
    background-color: rgba(0,0,0, 0.3);

    /* 行高属于控制文字的属性, 能继承 */
    line-height: 44px;
}

.banner .left span {
    float: right;
}

.banner .left a {
    font-size: 14px;
    color: #fff;
}

.banner .left a:hover {
    color: #00b4ff;
}

.banner .right {
    float: right;
    margin-top: 50px;
    width: 228px;
    height: 300px;
    background-color: #fff;
}

.banner .right h2 {
    height: 48px;
    background-color: #9bceea;
    text-align: center;
    line-height: 48px;
    font-size: 18px;
    color: #fff;
}

.banner .right .content {
    padding: 0 18px;
}

.banner .right .content dl {
    padding: 12px 0;
    border-bottom:2px solid #e5e5e5;
}

.banner .right .content dt {
    font-size: 16px;
    color: #4e4e4e;
}

.banner .right .content dd {
    font-size: 14px;
    color: #4e4e4e;
}

.banner .right .more {
    display: block;
    /* margin: 4px 14px 0; */
    margin: 4px auto 0;
    width: 200px;
    height: 40px;
    border: 1px solid #00a4ff;

    font-size: 16px;
    color: #00a4ff;
    font-weight: 700;

    text-align: center;
    line-height: 40px;
}

/* 精品推荐 */
.goods {
    margin-top: 8px;
    padding-left: 34px;
    padding-right: 26px;

    height: 60px;
    background-color: #fff;
    box-shadow: 0px 2px 3px 0px 
		rgba(118, 118, 118, 0.2);

    line-height: 60px;

}

.goods h2 {
    float: left;
    font-size: 16px;
    color: #00a4ff;
    font-weight: 400;
}

.goods ul {
    float: left;
    margin-left: 30px;
}

.goods ul li {
    float: left;
}

.goods li a {
    border-left: 1px solid #bfbfbf;
    padding: 0 30px;
    font-size: 16px;
    color: #050505;
}

.goods .xingqu {
    float: right;
    font-size: 14px;
    color: #00a4ff;
}

/* 精品课程 */
.box {
    margin-top: 35px;
}

.box .title {
    height: 40px;
}

.box .title h2 {
    float: left;
    font-size: 20px;
    color: #494949;
    font-weight: 400;
}

.box .title a {
    float: right;
    margin-right: 30px;
    font-size: 12px;
    color: #a5a5a5;
}

.box .content li {
    float: left;
    margin-right: 15px;
    margin-bottom: 15px;
    width: 228px;
    height: 270px;
    background-color: #fff;
}

.box .content li:nth-child(5n) {
    margin-right: 0;
}

.box .content li h3 {
    padding: 20px;
    font-size: 14px;
    color: #050505;
    font-weight: 400;
}

.box .content li p {
    padding: 0 20px;
    font-size: 12px;
    color: #999;
}

.box .content li span {
    color: #ff7c2d;
}

/* 版权 */
.footer {
    margin-top: 40px;

    padding-top: 30px;

    height: 417px;
    background-color: #fff;
}

.footer .left {
    float: left;
}

.footer .left  p {
    margin: 20px 0 10px;
    font-size: 12px;
    color: #666;
}

.footer .left a {
    display: inline-block;
    width: 120px;
    height: 36px;
    border: 1px solid #00a4ff;
    text-align: center;
    line-height: 36px;
    font-size: 16px;
    color: #00a4ff;
}

.footer .right {
    float: right;
}

.footer .right dl {
    float: left;
    margin-left: 120px;
}
```

