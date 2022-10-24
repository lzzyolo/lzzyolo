<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>gap year</title>
<style>
* {
  box-sizing: border-box;
}
 
body {
  color: #333;
  font-family: Arial;
  padding: 10px;
  background: #f1f1f1;
}
 
/* 头部标题 */
.header {
  padding: 30px;
  text-align: center;
  background: white;
}
 
.header h1 {
  font-size: 50px;
}
 
/* 导航条 */
.topnav {
  overflow: hidden;
  background-color: #333;
}
 
/* 导航条链接 */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
 
/* 链接颜色修改 */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}
 
/* 创建两列 */
/* Left column */
.leftcolumn {   
  float: left;
  width: 75%;
}
 
/* 右侧栏 */
.rightcolumn {
  float: left;
  width: 25%;
  background-color: #f1f1f1;
  padding-left: 20px;
}
 
/* 图像部分 */
.fakeimg {
  background-color: #333;
  width: 100%;
  padding: 20px;
}
 
/* 文章卡片效果 */
.card {
  background-color: white;
  padding: 20px;
  margin-top: 20px;
}
 
/* 列后面清除浮动 */
.row:after {
  content: "";
  display: table;
  clear: both;
}
 
/* 底部 */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}
 
/* 响应式布局 - 屏幕尺寸小于 800px 时，两列布局改为上下布局 */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}
 
/* 响应式布局 -屏幕尺寸小于 400px 时，导航等布局改为上下布局 */
@media screen and (max-width: 400px) {
  .topnav a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1>Gap   year</h1>
  <p>人生必经之过程</p>
</div>

<div class="topnav">
  <a href="mailto:"2495307256@qq.com>首页</a>
  <a href="picture.html">旅行足迹</a>
  <a href="#">旅行计划</a>
  <a href="1013.gif" style="float:right">联系方式</a>
</div>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>Gap year</h2>
      <h4>寻找自我的一种方式</h4>
      <img src="girl.jpg"width="900" height="400">
      <h4>什么是gap year?</h4>
      <p>指青年人暂时跳出现有的升学、工作轨道，用一年的空闲时间，去做一些自己想做的事情。旅行、做志愿者、陪陪家人，或者就是在家待着，为自己迎接未来的生活做好充分准备</p>
    </div>
    <div class="card">
      <h2>间隔的意义</h2>
      <h5>刘子照是一个很帅很帅的大帅哥</h5>
      <img src="1.png" width="700" height="430">
      <p>刘子照是一个很帅很帅的大帅哥</p>
      <p></p>
    </div>
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>关于我</h2>
      <img src="1010.jpg" width="300" height="300">
      <p>刘子照是一个很帅很帅的大帅哥</p>
    </div>
    <div class="card">
      <h3>热门文章</h3>
      <img src="lijiang.jpg" width="300" height="300">
    </div>
    <div class="card">
      <h3>更多选择</h3>
      <p>文本</p>
    </div>
  </div>
</div>

<div class="footer">
  <h1>朝碧海而暮苍梧</h1>
</div>

</body>
</html>
