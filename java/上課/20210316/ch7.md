# ch7 HTML

### attribute.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      [class*="apple"] {color: blue;}
    </style>
  </head>
  <body>
    <ul>
      <li class="apple">蘋果牛奶</li>
      <li class="apple-banana">香蕉蘋果牛奶</li>
      <li class="grape apple banana">特調牛奶</li>
      <li class="kiwifruit apple">特調果汁</li>
    </ul>
  </body>
</html>

```
### body.css
```
body {color: white; background: purple;}
```
### class.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
    <style>
      .odd {background: linen;}				/*類別選擇器*/
      .even {background: lightblue;}		/*類別選擇器*/
    </style>
  </head>
  <body>
    <table>
      <tr class="odd"><td>01</td><td>鳶尾花</td></tr>
      <tr class="even"><td>02</td><td>滿天星</td></tr>
      <tr class="odd"><td>03</td><td>香水百合</td></tr>
      <tr class="even"><td>04</td><td>鬱金香</td></tr>
    </table>
  </body>
</html>

```
### id.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      #btn1 {font-size: 20px; color: red;}		/*ID選擇器*/
      #btn2 {font-size: 20px; color: green;}	/*ID選擇器*/
    </style>
  </head>
  <body>
    <button id="btn1">按鈕1</button>
    <button id="btn2">按鈕2</button>
  </body>
</html>

```
### linkcss1.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
    <style>
      body {color: white; background: purple;}
    </style>
  </head>
  <body>
    <h1>Hello, CSS3!</h1>
  </body>
</html>

```
### link2.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
  </head>
  <body style="color: white; background: purple;">
    <h1>Hello, CSS3!</h1>
  </body>
</html>

```
### linkcss3.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
    <style>
      @import url("body.css");
    </style>
  </head>
  <body>
    <h1>Hello, CSS3!</h1>
  </body>
</html>

```
### linkcss4.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
    <link rel="stylesheet" href="body.css" type="text/css">
  </head>
  <body>
    <h1>Hello, CSS3!</h1>
  </body>
</html>

```
### novel1.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
  </head>
  <body>
  </body>
</html>
```
### novel2.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
  </head>
  <body>
  </body>
</html>

```
### pseudo1.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
    <style>
      p::first-line {color: red;} 								/*虛擬元素*/
      p::after {content: "(王維《相思》)"; color: blue;}			/*虛擬元素*/
    </style>
  </head>
  <body>
    <p>紅豆生南國，<br>
       春來發幾枝。<br>
       願君多採擷，<br>
       此物最相思。</p>
  </body>
</html>

```
### pseudo2.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
    <style>
      a:link {color: black;}					/*虛擬類別*/
      a:visited {color: red;}					/*虛擬類別*/
    </style>
  </head>
  <body>
    <ul>
      <li><a href="novel1.html">射雕英雄傳</a></li>
      <li><a href="novel2.html">倚天屠龍記</a></li>
      <li><a href="novel3.html">天龍八部</a></li>
      <li><a href="novel4.html">笑傲江湖</a></li>
    </ul>
  </body>
</html>

```
### pseudo3.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
    <style>
      h1 {background: linen;}						/*類型選擇器*/
      h1:hover {background: lightblue;} 			/*虛擬類別*/
    </style>
  </head>
  <body>
    <h1>蝶戀花</h1>
    <h1>卜算子</h1>
    <h1>臨江仙</h1>
  </body>
</html>
```
### sample1.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
  </head>
  <body>
    <h1>暮光之城</h1>
  </body>
</html>

```
### sample2.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>我的網頁</title>
    <style>
      h1 {
	    color: red; 
		font-family: 標楷體;
	  }
    </style>
  </head>
  <body>
    <h1>暮光之城</h1>
  </body>
</html>

```
