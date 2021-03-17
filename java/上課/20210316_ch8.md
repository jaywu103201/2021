# ch8 HTML
```
http://srdesign.com.tw/design/thread-536-1-1.html
```

### color.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>   
    <h1 style="color: #00ff00;">卜算子</h1>
    <h1 style="color: rgb(255, 0, 0);">蝶戀花</h1>
    <h1 style="color: rgba(255, 0, 0, 0.5);">蝶戀花</h1>
    <h1 style="color: hsl(240, 100%, 50%);">臨江仙</h1>
    <h1 style="color: hsla(240, 100%, 50%, 0.3);">臨江仙</h1>
  </body>
</html>
```
### color2.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body style="background-color: pink;">
    <h1 style="background-color: rgba(255, 255, 255, 0.5);">卜算子</h1>
  </body>
</html>
```
### color3.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <img src="fig1.jpg" width="200">
    <img src="fig1.jpg" width="200" style="opacity: 0.5;">
    <h1 style="color: navy;">豪斯登堡吉祥物</h1>
    <h1 style="color:navy; opacity: 0.5;">豪斯登堡吉祥物</h1>   /*opacity透明度*/
  </body>
</html>
```
### font1.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      p {font-family: 標楷體, 微軟正黑體;}
    </style>
  </head>
  <body>   
    <p>雲母屏風燭影深，長河漸落曉星沉。<br>
       嫦娥應悔偷靈藥，碧海青天夜夜心。</p>
  </body>
</html>

```
### font2.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <p style="font-size: 20px;">生日快樂Happy Birthday</p>
    <p style="font-size: 20pt;">生日快樂Happy Birthday</p>
    <p style="font-size: xx-small;">生日快樂Happy Birthday</p>
    <p style="font-size: x-small;">生日快樂Happy Birthday</p>
    <p style="font-size: small;">生日快樂Happy Birthday</p>
    <p style="font-size: medium;">生日快樂Happy Birthday</p>
    <p style="font-size: large;">生日快樂Happy Birthday</p>
    <p style="font-size: x-large;">生日快樂Happy Birthday</p>
    <p style="font-size: xx-large;">生日快樂Happy Birthday</p>
  </body>
</html>
```
### font3.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      p {font-style: italic;}
    </style>
  </head>
  <body>
    <p>雲母屏風燭影深，長河漸落曉星沉。<br>
       嫦娥應悔偷靈藥，碧海青天夜夜心。</p>
  </body>
</html>

```
### font4.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <h1 style="font-weight: bold;">Hello, world!</h1>
    <h1 style="font-weight: normal;">Hello, world!</h1>
    <h1 style="font-weight: bolder;">Hello, world!</h1>
  </body>
</html>
```
### font5.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <h1 style="font-variant: normal;">Hello, world!</h1>
    <h1 style="font-variant: small-caps;">Hello, world!</h1>
  </body>
</html>
```
### font6.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <p style="line-height: normal;">雲母屏風燭影深，長河漸落曉星沉。<br>
      嫦娥應悔偷靈藥，碧海青天夜夜心。</p>
    <p style="line-height: 2;">冰簟銀床夢不成，碧天如水夜云輕。<br>
      雁聲遠過瀟湘去，十二樓中月自明。</p>
  </body>
</html>
```
### font7.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <p style="font: italic 20px/25px 標楷體;">
	  雲母屏風燭影深，長河漸落曉星沉。<br>
      嫦娥應悔偷靈藥，碧海青天夜夜心。</p>
  </body>
</html>
```
### list1.html
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      ul {list-style-type: square;}
    </style>
  </head>
  <body> 
    <ul>
      <li>射鵰英雄傳</li>
      <li>天龍八部</li>
      <li>倚天屠龍記</li>
      <li>笑傲江湖</li>
      <li>鹿鼎記</li>
    </ul>
  </body>
</html>
```
### list2.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      ol {list-style-type: upper-alpha;}
    </style>
  </head>
  <body>
    <ol>
      <li>射鵰英雄傳</li>
      <li>天龍八部</li>
      <li>倚天屠龍記</li>
      <li>笑傲江湖</li>
      <li>鹿鼎記</li>
    </ol>
  </body>
</html>

```
### list3.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      ul {list-style-image: url(blockgrn.gif);}
    </style>
  </head>
  <body> 
    <ul>
      <li>魔戒首部曲：魔戒現身</li>
      <li>魔戒二部曲：雙城奇謀</li>
      <li>魔戒三部曲：王者再臨</li>
    </ul>
  </body>
</html>

```
### list4.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      ul {list-style: outside;}
      ul.compact {list-style: inside;}
    </style>
  </head>
  <body>
    <ul>
      <li>台灣野鳥</li>
    </ul>
    <ul class="compact">
      <li>黑面琵鷺最早的棲息地是韓國及中國的北方沿海，但近年來它們覓著
         了一個新的棲息地，就是台灣的曾文溪口沼澤地。</li>
      <li>八色鳥在每年的夏天會從東南亞地區飛到台灣繁殖下一代，由於羽色
         艷麗(八種顏色)，可以說是山林中的漂亮寶貝。</li>
    </ul>
  </body>
</html>

```
### list5.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <style>
      ul {list-style: url(star.gif) upper-roman;}
    </style>
  </head>
  <body> 
    <ul>
      <li>魔戒首部曲：魔戒現身</li>
      <li>魔戒二部曲：雙城奇謀</li>
      <li>魔戒三部曲：王者再臨</li>
    </ul>
  </body>
</html>

```
### text1.html
```

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <p style="text-indent: 1cm;">庭院深深深幾許？楊柳堆煙，簾幕無重數。
      玉勒雕鞍遊冶處，樓高不見章台路。雨橫風狂三月暮，門掩黃昏，
      無計留春住。淚眼問花花不語，亂紅飛過鞦韆去。</p>
  </body>
</html>
```
### text2.html
```
<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <p style="text-align: left;">庭院深深深幾許？楊柳堆煙，簾幕無重數。
	  玉勒雕鞍遊冶處，樓高不見章台路。雨橫風狂三月暮，門掩黃昏，
      無計留春住。淚眼問花花不語，亂紅飛過鞦韆去。</p>
    <p style="text-align: right;">庭院深深深幾許？楊柳堆煙，簾幕無重數。
      玉勒雕鞍遊冶處，樓高不見章台路。雨橫風狂三月暮，門掩黃昏，
      無計留春住。淚眼問花花不語，亂紅飛過鞦韆去。</p>
    <p style="text-align: center;">庭院深深深幾許？楊柳堆煙，簾幕無重數。
      玉勒雕鞍遊冶處，樓高不見章台路。雨橫風狂三月暮，門掩黃昏，
      無計留春住。淚眼問花花不語，亂紅飛過鞦韆去。</p>    
  </body>
</html>
```
### text3.html
```

<!DOCTYPE html>
<html> 
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <p style="letter-spacing: normal;">Happy Birthday to You!</p>
    <p style="letter-spacing: 3px;">Happy Birthday to You!</p>
    <p style="letter-spacing: 0.25cm;">Happy Birthday to You!</p>
  </body>
</html>
```
### text4.html
```

<!doctype html> 
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <p style="word-spacing: normal;">Happy Birthday to You!</p>    
    <p style="word-spacing: 8px;">Happy Birthday to You!</p>	
    <p style="word-spacing: 1cm;">Happy Birthday to You!</p> 
  </body>
</html>
```
### text5.html
```

<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <p style="text-transform: none;">Happy Birthday to You!</p>
    <p style="text-transform: capitalize;">Happy Birthday to You!</p>
    <p style="text-transform: uppercase;">Happy Birthday to You!</p>
    <p style="text-transform: lowercase;">Happy Birthday to You!</p>
  </body>
</html>
```
### text6.html
```
<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <p style="white-space: pre;">
    void main()
    {
        printf("Hello, world!\n");
    }  
	</p>    
  </body>
</html>
```
### text7.html
```
<!DOCTYPE html>
<html> 
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <h1 style="text-shadow: 12px 8px 5px orange;">Hello, world!</h1>
    <h1 style="text-shadow: -12px -8px 5px orange;">Hello, world!</h1>
    <h1 style="text-shadow: 10px 10px 2px cyan, 20px 20px 2px silver;">Hello, world!</h1>
  </body>
</html>
```
### text8.html
```

<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <h1 style="text-decoration-line: overline;
      text-decoration-style: dotted; 
      text-decoration-color: red;">臨江仙</h1>
    <h1 style="text-decoration-line: underline;
      text-decoration-style: wavy; 
      text-decoration-color: cyan;">蝶戀花</h1>
	<h1 style="text-decoration-line: line-through;
      text-decoration-style: solid; 
      text-decoration-color: blue;">卜算子</h1>  
  </body>
</html>
```
### text9.html
```
<!DOCTYPE html> 
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body> 
    <h1 style="text-decoration: overline dotted red;">臨江仙</h1>
    <h1 style="text-decoration: underline wavy cyan;">蝶戀花</h1>
	<h1 style="text-decoration: line-through solid blue;">卜算子</h1>  
  </body>
</html>
```
