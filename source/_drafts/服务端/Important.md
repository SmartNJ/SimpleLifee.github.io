---
title: Important
tags:
---

// Custom styles.
// Custom styles.
/*首页文章阴影样式*/
body{
  z-index:9;
}
.post {
  margin-bottom: 100px;
  padding: 25px;
  -webkit-box-shadow: 0 0 14px rgba(202,203,203,1);
  -moz-box-shadow: 0 0 14px rgba(202,203,204,1);
  background: #fff;
}
.posts-expand .post-eof {
  display: block;
  margin: 0px auto 60px;
  width: 8%;
  height: 1px;
  background: #ccc;
  text-align: center;
}

/*首页点击出现下划线*/
.posts-expand .post-title-link:hover::before {
  visibility: visible;
  -webkit-transform: scaleX(1);
  -moz-transform: scaleX(1);
  -ms-transform: scaleX(1);
  -o-transform: scaleX(1);
  transform: scaleX(1);
}
.posts-expand .post-title-link{
  margin-bottom 20px;
  display: inline-block;
  position: relative;
  color: #555;
  border-bottom: none;
  line-height: 2.2;
  vertical-align: top;
}
/*侧边栏博客链接前面小圆圈颜色*/
.links-of-author a:before{
  color:#fff;
}

.bg_content{
  position: fixed;
  top: 0;
  z-index: -1;
  width: 100%;
  height: 100%;
}
#canvas{
  width: 100%;
  height:100%;
}
/*将头部背景变为透明*/
.header{
  background: transparent ;
}
@media (max-width: 767px){
  .menu {
    text-align: right;
  }
}
/*头像改为圆形，hover转动*/
.site-author-image {
  display: block;
  margin: 15px auto;
  /*padding: $site-author-image-padding;*/
  max-width: $site-author-image-width;
  height: $site-author-image-height;
  /*
  border: $site-author-image-border-width solid $site-author-image-border-color;
  */
  border-radius:50%;
  -webkit-transition: all 0.5s;
  -moz-transition: all 0.5s;
  -ms-transition: all 0.5s;
  -o-transition: all 0.5s;
  transition: all 0.5s;
}
.site-author-image:hover{
  -webkit-box-shadow:0 0 10px rgba(0,0,0,0.5);
  -moz-box-shadow:0 0 10px rgba(0,0,0,0.5);
  box-shadow:0 0 10px rgba(0,0,0,0.5);
  webkit-transform: rotate(360deg) scale(1.1);
  moz-transform: rotate(360deg) scale(1.1);
  ms-transform: rotate(360deg) scale(1.1);
  transform: rotate(360deg) scale(1.1);

}
@media (max-width: 767px) {

  .site-nav-toggle {
    display: none;
    position: absolute;
    top: 10px;
    right: 10px;
  }
}
