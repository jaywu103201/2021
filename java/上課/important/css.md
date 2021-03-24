# html 
## css 網站
```
@charset "utf-8";

/*視窗背景色設定*/
body {
  background: #fbf9cc url(img/bg.png) repeat-x;
}

/*連結顏色設定*/
a {
  color: #df4839;
}
a:hover {
  color: #ff705b;
  text-decoration: none;
}

/*頁首,導覽,頁尾的共通設定*/
header,nav,footer {
  text-align: center;
}

/*導覽樣式設定*/


/*頁面標題設定*/
h1 {
  width: 300px;
  margin: 40px auto;
  padding: 30px;
  border: 5px solid #95dbbd;
  background-color: #6fbb9a;
  color: #fff;
  font-size: 300%;
  text-align: center;
  line-height: 1;
  border-radius: 50%;
  text-shadow: 1px 1px 2px #307657;
  box-shadow: 0 0 10px rgba(0,0,0,0.5);
  background-image: linear-gradient(to bottom, #6fbb9a, #4a9d79);
  font-family: 'Limelight', cursive;
}

/*次標題設定*/
.h {
  padding: 10px;
  margin-bottom: 30px;
  border: 1px dotted #94c8b1;
  border-left: 10px solid #d0e35b;
  color: #6fbb9a;
  border-radius: 5px 0 0 5px;
}


/*小標題設定*/
.h-sub {
  padding: 10px;
  background-color: #fbf9cc;
  color: #ff705b;
  border-radius: 10px;
  box-shadow: 0 0 5px 2px #ffd0ad inset;
}
.h-sub span{
  font-weight: normal;
}

/*內容區塊邊框設定*/
#contents {
  margin: 40px;
  padding: 40px 80px;
  border: 1px solid #f6bb9e;
  background-color: #fff;
}

/*「更多介紹」連結設定*/
.more {
  text-align: right;
}
.more::after {
  content: url(img/ico_arrow.png);
  margin-left: 3px;
  vertical-align: middle;
}

/*連結圖示設定*/
a[target="_blank"]::after {
  content: url(img/ico_blank.png);
  margin-left: 5px;
  vertical-align: middle;
}
a[href^="mailto:"]::after {
  content: url(img/ico_mail.png);
  margin-left: 5px;
  vertical-align: middle;
}

/*區塊間分隔*/
#contents > section + section {
  margin-top: 80px;
}

/*文繞圖設定*/


/*圓形圖片設定*/
.img-round {
  border-radius: 50%;
}


```
# important
```
xampp
htdocs
036
http://120.114.135.244/036/
```
# html homework
```
<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<title>KOMA-NATSU Web</title>
<meta name="viewport" content="width=device-width,initial-scale:1">
<meta name="keywords" content="貓咪,喵咪,喵星人,貓咪介紹,曬貓">
<meta name="description" content="介紹我家的貓咪們！還有大量可愛的貓照片。">
<link href="style.css" rel="stylesheet" media="all">
<link href="https://fonts.googleapis.com/css?family=Limelight" rel="stylesheet">
</head>

<body>
<header>
  <h1>KOMA-NATSU Web</h1>
  <p>介紹一下我家的偶像貓咪們！</p>
</header>

<nav>
  <ul class="menu">
    <li><a href="#intro">關於本站</a></li>
    <li><a href="#cats">我家的貓咪</a></li>
    <li><a href="#profile">飼主介紹</a></li>
  </ul>
</nav>

<main id="contents">

<section id="intro">
  <h2 class="h">關於本站</h2>
  <p>歡迎光臨本站。<br>
  這裡是介紹我家貓主子姐妹的曬貓網站，有大量的可愛相片。<br>
  <strong>※未經許可，請勿擅自複製轉載。</strong></p>
</section>

<section id="cats">
  <h2 class="h">我家的貓咪</h2>

  <section>
    <h3 class="h-sub">●小町<span>（KOMACHI・♀）</span></h3>
    <img src="img/komachi.jpg" width="480" height="320" alt="小町" class="imgL">
    <p>出生不到2個月就抱回來的貓姐姐。<br>
從出生就是養在溫室裡的花朵，所以非常膽小怕生。因為太怕生，只要聽到門鈴聲就會躲起來，所以就算是來我家的客人也難以見到。</p>
    <p class="more clear"><a href="cats/komachi.html">更多介紹</a></p>
  </section>

  <section>
    <h3 class="h-sub">●小夏<span>（KONATSU・♀）</span></h3>
    <img src="img/konatsu.jpg" width="480" height="320" alt="小夏" class="imgR">
    <p>為了讓小町有個伴，在1年後抱回來的貓妹妹。<br>
  原本是在埼玉縣飯能市的煤礦場出生長大的小野貓。和小町不同，是個性活潑親人，愛吃、愛玩、愛睡的元氣寶寶。</p>
    <p class="more clear"><a href="cats/konatsu.html">更多介紹</a></p>
  </section>

</section>


<section id="profile" class="clearfix">
  <h2 class="h">飼主介紹</h2>
  <img src="img/avatar.png" width="250" height="250" alt="大頭照" class="img-round imgL">
  <dl>
    <dt>暱稱 ：</dt><dd>roka404</dd>
    <dt>職業 ：</dt><dd>Web相關工作的SOHO族</dd>
    <dt>mail ：</dt><dd><a href="mailto:info@roka404.main.jp">info@roka404.main.jp</a></dd>
    <dt>Web ：</dt><dd><a href="http://roka404.main.jp/blog/" target="_blank">http://roka404.main.jp/blog/</a></dd>
  </dl>
</section>

</main>

<footer>
  <p><small>Copyright © KOMA-NATSU Web All Rights Reserved.</small></p>
</footer>
</body>
</html>


```
```
@charset "utf-8";

/*圖片伸縮設定*/
img {
  max-width: 100%;
  height: auto;
}

/*視窗背景色設定*/
body {
  background: #fbf9cc url(img/bg.png) repeat-x;
}

/*連結顏色設定*/
a {
  color: #df4839;
}
a:hover {
  color: #ff705b;
  text-decoration: none;
}

/*頁首,導覽,頁尾的共通設定*/
header,nav,footer {
  text-align: center;
}

/*導覽樣式設定*/
.menu {
  margin: 0;
  padding: 0;
}
.menu li {
  list-style-type: none;
  display: inline-block;
  width: 180px;
  margin: 0 10px;
}
.menu a {
  display: block;
  padding: 10px;
  background: #6fbb9a;
  border-radius: 8px;
  color: #fff;
  text-decoration: none;
}
.menu a:hover {
  background: #90ddbb;
}

/*頁面標題設定*/
h1 {
  width: 300px;
  margin: 40px auto;
  padding: 30px;
  border: 5px solid #95dbbd;
  background-color: #6fbb9a;
  color: #fff;
  font-size: 300%;
  text-align: center;
  line-height: 1;
  border-radius: 50%;
  text-shadow: 1px 1px 2px #307657;
  box-shadow: 0 0 10px rgba(0,0,0,0.5);
  background-image: linear-gradient(to bottom, #6fbb9a, #4a9d79);
  font-family: 'Limelight', cursive;
}

/*次標題設定*/
.h {
  padding: 10px;
  margin-bottom: 30px;
  border: 1px dotted #94c8b1;
  border-left: 10px solid #d0e35b;
  color: #6fbb9a;
  border-radius: 5px 0 0 5px;
}


/*小標題設定*/
.h-sub {
  padding: 10px;
  background-color: #fbf9cc;
  color: #ff705b;
  border-radius: 10px;
  box-shadow: 0 0 5px 2px #ffd0ad inset;
}
.h-sub span{
  font-weight: normal;
}

/*內容區塊邊框設定*/
#contents {
  box-sizing: border-box;
  max-width: 960px;
  margin: 40px auto;
  padding: 4% 8%;
  border: 1px solid #f6bb9a;
  background-color: #fff;
}

/*貓咪照片寬度*/
#cats img {
  width: 60%;
}

/*「更多介紹」連結設定*/
.more {
  text-align: right;
}
.more::after {
  content: url(img/ico_arrow.png);
  margin-left: 3px;
  vertical-align: middle;
}

/*連結圖示設定*/
a[target="_blank"]::after {
  content: url(img/ico_blank.png);
  margin-left: 5px;
  vertical-align: middle;
}
a[href^="mailto:"]::after {
  content: url(img/ico_mail.png);
  margin-left: 5px;
  vertical-align: middle;
}

/*區塊間分隔*/
#contents > section + section {
  margin-top: 80px;
}

/*文繞圖設定*/
.imgL {
  float: left;
  margin-right: 20px;
}
.imgR {
  float: right;
  margin-left: 20px;
}
.clear {
  clear: both;
}
.clearfix::after {
  content: "";
  display: block;
  clear: both;
}

/*圓形圖片設定*/
.img-round {
  border-radius: 50%;
}


```
