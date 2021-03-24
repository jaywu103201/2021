## html ch9
### border1.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <img src="cake.jpg" style="border: dotted;">
	<img src="cake.jpg" style="border: double;">
  </body>
</html>
```
### border2.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <h1 style="border-style: double; border-color: green;">美味的甜點</h1>
    <img src="cake.jpg" style="border-style: solid; border-color: orange;">
  </body>
</html>

```
### border3.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <img src="cake.jpg" style="border-style: solid; border-width: thin">
    <img src="cake.jpg" style="border-style: solid; border-width: medium"><br>
    <img src="cake.jpg" style="border-style: solid; border-width: thick">
    <img src="cake.jpg" style="border-style: solid; border-width: 10px">
  </body>
</html>

```
### border4.html
```
<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">	
  </head>
  <body>
    <h1 style="border: solid 10px hotpink;">蝶戀花</h1>
  </body>
</html>
```
### border5.html
```
<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">	
  </head>
  <body>
    <h1 style="border: solid 10px hotpink; border-radius: 10px;">蝶戀花</h1>
  </body>
</html>
```
### box0.html
```
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Box Model</title>	
  </head>
  <body>
    <img src="jp5.jpg" style="border:solid 5px orange; width:300px; height:300px; object-fit:fill">	
  </body>
</html>
```
### box1.html
```
<!doctype html> 
<html>
  <head>
    <meta charset="utf-8">
    <title>Box Model</title>	
  </head>
  <body>
    <img src="flower2.gif" style="border:solid 5px orange; width:150px; height:150px; object-fit:none; object-position:left top">
	<img src="flower2.gif" style="border:solid 5px orange; width:150px; height:150px; object-fit:none; object-position:50% 50%">
  </body>
</html>
```
### boxshadow.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>	
  <body>
    <h1 style="width: 400px; background-color: lightpink;
      box-shadow: 10px 10px 5px lightgray;">臨江仙</h1>
    <h1 style="width: 400px; background-color: lightblue;
      box-shadow: 10px 10px 5px lightgray, 20px 20px 20px lightyellow;">卜算子</h1>
  </body>
</html>
```
### display.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
	<style>
	  img{
	    width: 40%; 
		display: block; 
		margin: 10px auto;
	  }
	</style>
  </head>
  <body>
    <img src="cake.jpg">
  </body>
</html>
```
### float1.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
	<title>文繞圖</title>
	<style>
      img {float: none;}
    </style>
  </head>	
  <body>
    <img src="jp2.jpg" width="300">
	<h1>豪斯登堡</h1>
    <p>豪斯登堡位於日本九州，一處重現中古世紀歐洲街景的渡假勝地，命名由來是荷蘭女王陛下所居住的宮殿豪斯登堡宮殿。</p>
	<p>園內風景怡人俯拾皆畫，還有『ONE PIECE 航海王』的世界，乘客可以搭上千陽號來一趟冒險之旅。</p>	  
  </body>
</html>
```
### float2.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
	<title>文繞圖</title>
	<style>
      img {float: left;}
    </style>
  </head>	
  <body>
    <img src="jp2.jpg" width="300">
	<h1>豪斯登堡</h1>
    <p>豪斯登堡位於日本九州，一處重現中古世紀歐洲街景的渡假勝地，命名由來是荷蘭女王陛下所居住的宮殿豪斯登堡宮殿。</p>
	<p style="clear: left;">園內風景怡人俯拾皆畫，還有『ONE PIECE 航海王』的世界，乘客可以搭上千陽號來一趟冒險之旅。</p>	  
  </body>
</html>
```
### margin.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
	<style>
	  h1 {text-align: center;}
	  p {background-color: lightyellow;}
	</style>
  </head>
  <body> 
    <h1>醉翁亭記</h1>
    <p style="margin: 1cm 0.5cm;">環滁皆山也。其西南諸峰，林壑尤美。望之蔚然而深秀者，琅琊也。山行六七里，漸聞水聲潺潺；而泄出於兩峰之間者，釀泉也。峰迴路轉，有亭翼然，臨於泉上者，醉翁亭也。作亭者誰？山之僧智遷也。名之者誰？太守自謂也。太守與客來飲於此，飲少輒醉，而年又最高，故自號曰醉翁也。醉翁之意不在酒，在乎山水之間也。山水之樂，得之心而寓之酒也。</p>
    <p>若夫日出而林霏開，雲歸而巖穴暝，晦明變化者，山間之朝暮也。野芳發而幽香，佳木秀而繁蔭，風霜高潔，水落而石出者，山間之四時也。朝而往，暮而歸，四時之景不同，而樂亦無窮也。</p>
  </body>
</html>
```
### maxheight.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <p style="background-color: lightyellow; width: 400px; max-height: 100px;">環滁皆山也。其西南諸峰，林壑尤美。望之蔚然而深秀者，琅琊也。山行六七里，漸聞水聲潺潺；而泄出於兩峰之間者，釀泉也。峰迴路轉，有亭翼然，臨於泉上者，醉翁亭也。作亭者誰？山之僧智遷也。名之者誰？太守自謂也。太守與客來飲於此，飲少輒醉，而年又最高，故自號曰醉翁也。醉翁之意不在酒，在乎山水之間也。山水之樂，得之心而寓之酒也。</p>
  </body>
</html>
```
### maxwidth.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <h1 style="background-color: lightgreen; max-width: 450px;">醉翁亭記</h1>
  </body>
</html>
```
### overflow.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <p style="background-color: lightyellow; width: 400px; max-height: 100px; overflow: auto;">環滁皆山也。其西南諸峰，林壑尤美。望之蔚然而深秀者，琅琊也。山行六七里，漸聞水聲潺潺；而泄出於兩峰之間者，釀泉也。峰迴路轉，有亭翼然，臨於泉上者，醉翁亭也。作亭者誰？山之僧智遷也。名之者誰？太守自謂也。太守與客來飲於此，飲少輒醉，而年又最高，故自號曰醉翁也。醉翁之意不在酒，在乎山水之間也。山水之樂，得之心而寓之酒也。</p>
  </body>
</html>
```
### padding.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
	<style>
	  h1 {text-align: center;}
	  p {background-color: lightyellow; font: 標楷體;}
	</style>
  </head>
  <body> 
    <h1>醉翁亭記</h1>
    <p style="padding: 0.5cm 1cm;">環滁皆山也。其西南諸峰，林壑尤美。望之蔚然而深秀者，琅琊也。山行六七里，漸聞水聲潺潺；而泄出於兩峰之間者，釀泉也。峰迴路轉，有亭翼然，臨於泉上者，醉翁亭也。作亭者誰？山之僧智遷也。名之者誰？太守自謂也。太守與客來飲於此，飲少輒醉，而年又最高，故自號曰醉翁也。醉翁之意不在酒，在乎山水之間也。山水之樂，得之心而寓之酒也。</p>
    <p>若夫日出而林霏開，雲歸而巖穴暝，晦明變化者，山間之朝暮也。野芳發而幽香，佳木秀而繁蔭，風霜高潔，水落而石出者，山間之四時也。朝而往，暮而歸，四時之景不同，而樂亦無窮也。</p>
  </body>
</html>
```
### position1.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      p {display: block; line-height: 2;}
      span {display: inline;}
      .note {font-size: 12px; color: blue;}
    </style>
  </head>
  <body>
    <p>庭院深深深幾許？ 楊柳堆煙，簾幕無重數。
       <span class="note">註釋1：堆煙意指楊柳濃密</span></p>
    <p>玉勒雕鞍遊冶處，樓高不見章臺路。
       <span class="note">註釋2：章台路意指歌妓聚居之所</span></p>
    <p>雨橫風狂三月暮，門掩黃昏，無計留春住。</p>
    <p>淚眼問花花不語，亂紅飛過秋千去。
       <span class="note">註釋3：亂紅意指落花</span></p>
  </body>
</html>

```
### position2.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      p {display: block; line-height: 2;}
      span {display: inline;}
      .note {position: relative; top: 10px; font-size: 12px; color: blue;}
    </style>
  </head>
  <body>
    <p>庭院深深深幾許？ 楊柳堆煙，簾幕無重數。
       <span class="note">註釋1：堆煙意指楊柳濃密</span></p>
    <p>玉勒雕鞍遊冶處，樓高不見章臺路。
       <span class="note">註釋2：章台路意指歌妓聚居之所</span></p>
    <p>雨橫風狂三月暮，門掩黃昏，無計留春住。</p>
    <p>淚眼問花花不語，亂紅飛過秋千去。
       <span class="note">註釋3：亂紅意指落花</span></p>
  </body>
</html>

```
### position3.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
	  img {display: inline; position: absolute; top: 20px; left: 300px;}
      p {display: block; width: 300px; white-space: pre-line;}      
    </style>
  </head>
  <body>
    <img src="flowers.jpg">
    <h1>妹妹背著洋娃娃</h1>
    <p>妹妹背著洋娃娃
       走到花園來看花
       娃娃哭了叫媽媽
       樹上小鳥笑哈哈</p>
	<h1>泥娃娃</h1>   
	<p>泥娃娃　
	   泥娃娃
	   一個泥娃娃
	   也有那眉毛
	   也有那眼睛
	   眼睛不會眨
       泥娃娃
	   泥娃娃
	   一個泥娃娃
       也有那鼻子
	   也有那嘴巴
       嘴巴不說話
       她是個假娃娃
	   不是個真娃娃
       她沒有親愛的媽媽
	   也沒有爸爸
	   泥娃娃
	   泥娃娃
	   一個泥娃娃
	   我做她媽媽
	   我做她爸爸
	   永遠愛著她</p>           
  </body>
</html>


```
### position4.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
	  img {display: inline; position: fixed; top: 20px; left: 300px;}
      p {display: block; width: 300px; white-space: pre-line;}      
    </style>
  </head>
  <body>
    <img src="flowers.jpg">
    <h1>妹妹背著洋娃娃</h1>
    <p>妹妹背著洋娃娃
       走到花園來看花
       娃娃哭了叫媽媽
       樹上小鳥笑哈哈</p>
	<h1>泥娃娃</h1>   
	<p>泥娃娃　
	   泥娃娃
	   一個泥娃娃
	   也有那眉毛
	   也有那眼睛
	   眼睛不會眨
       泥娃娃
	   泥娃娃
	   一個泥娃娃
       也有那鼻子
	   也有那嘴巴
       嘴巴不說話
       她是個假娃娃
	   不是個真娃娃
       她沒有親愛的媽媽
	   也沒有爸爸
	   泥娃娃
	   泥娃娃
	   一個泥娃娃
	   我做她媽媽
	   我做她爸爸
	   永遠愛著她</p>           
  </body>
</html>

```
### top.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
 	  div {background: cyan; position: absolute; 
        top: 15%; right: 20%; bottom: 30%; left: 40%;}
    </style>
  </head>
  <body>
    <div></div>
  </body>
</html>

```
### vertical1.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      #img1 {vertical-align: text-top; }
      #img2 {vertical-align: text-bottom; }
      #img3 {vertical-align: middle;}
      #img4 {vertical-align: 30px; }
    </style>
  </head>
  <body>
    <p>航海王<img id="img1" src="piece1.jpg" width="100px">喬巴</p>
    <p>航海王<img id="img2" src="piece1.jpg" width="100px">喬巴</p>
    <p>航海王<img id="img3" src="piece1.jpg" width="100px">喬巴</p>
    <p>航海王<img id="img4" src="piece1.jpg" width="100px">喬巴</p>
  </body>
</html>

```
### vertical2.html
```
<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">
  </head>	
  <body>
    <h1>H<span style="vertical-align: sub;">2</span>O</h1>
	<h1>H<span style="vertical-align: sub; font-size: 16px;">2</span>O</h1>
    <h1>X<span style="vertical-align:s upper;">2</span>Y</h1>
    <h1>X<span style="vertical-align:s upper; font-size: 16px;">2</span>Y</h1>	
  </body>
</html>
```
### visibility.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>	
  <body>
    <h1 style="background-color: lightpink;">臨江仙</h1>
	<h1 style="background-color: lightblue;">卜算子</h1>
  </body>
</html>
```
### width.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <p style="background-color: lightyellow; width: 400px; height: 175px;">環滁皆山也。其西南諸峰，林壑尤美。望之蔚然而深秀者，琅琊也。山行六七里，漸聞水聲潺潺；而泄出於兩峰之間者，釀泉也。峰迴路轉，有亭翼然，臨於泉上者，醉翁亭也。作亭者誰？山之僧智遷也。名之者誰？太守自謂也。太守與客來飲於此，飲少輒醉，而年又最高，故自號曰醉翁也。醉翁之意不在酒，在乎山水之間也。山水之樂，得之心而寓之酒也。</p>
  </body>
</html>
```
### zindex.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <img src="jp2.jpg" style="position: absolute; top: 10px; left: 10px; z-index: 1;">
    <h1 style="background-color: rgba(255, 255, 0, 0.3); width: 472px;
      position: absolute; top: 100px; left: 10px; z-index: 2;">豪斯登堡</h1>
  </body>
</html>

```
