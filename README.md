# mistakes-in--web-design
#index.html
<html>
     <head>
          <title>Ошибки в веб-дизайне</title>
          <link rel="stylesheet" href="style.css">
     </head>
     <body>
          <h1>Ошибки в веб-дизайне</h1>
          <article>
          <div>
               <p class="side">Новое обновление в игре! <br><span class="bside">больше врагов!</span><br><span class="cside">больше предметов!</span><br><span class="dside">تنةهف نتقبصلاض</span></p>
               <p class="vine">№1:<b>МНОГО ЦВЕТОВ И СТИЛЕЙ</b> <br>Для выделения частей сайта не нужно много цветов, ведь они путают пользователей и не позваляют выделить главные части. Достаточно 1 основного цвета и 1-2 для выделения. Тоже самое со стилями текста, но они не так сильно путают</p>
          </div>
          </article>
          <article>
          <div>
               <div class="wew">
               <p>Как похудеть? Всё просто! Нужно выполнить следующие действия</p>
               <p class="wiw">Ешьте 2 раза в день</p>
               <p class="waw">Не ходите в "фаст фуд"</p>
               </div>
               <p class="vini">№2:<b>ОТСТУПЫ</b> <br>Отступы между одинаковыми по смыслу блоками (например текстом) должны быть также одинаковыми, иначе будет свалка. Отступы должны быть не слишком маленькими и не слишком большими</p>
          </div>
          </article>
          <article>
          <div>
               <div class="ten">
               <h3>Как похудеть?</h3>
               <h3>Для начала:</h3>
               <h3>Ешьте здоровую пищу</h3>
               </div>
               <p class="blyat">№3:<b>ВЫДЕЛЕНИЕ</b> <br>Нужно хорошо выделять главные части сайта. Не нужно бояться делать более <b>жирный</b> шрифт, яркие или темные цвета, особые шрифты, но при этом нужно сохранять общий стиль сайта и не забывать о первом правиле</p>
          </div>
          </article>
          <article>
          <div>
               <
               <p>№4:<b>ЛОГОТИП</b> <br>Логотип задает стиль сайту. Например, если в логотипе есть закругленые края, то большая часть текста не должна быть с резким шрифтом </p>
          </div>
          </article>
     </body>
</html>

#style.css
body {
    font-family:sans-serif;
    background-color: black;
}

h1 {
    text-align: center;
    color: white;
}

p {
    float: right;
}

article {
    height: 220px;
    width: 400px;
    background-color: lightgrey;
    margin-top: 25px;
    position: relative;
    display: flex;
}

div:hover {
    background-color: white;
    transform: translateX(550px);
    transition:0.5s ease-in-out ;
}

.side {
    position: relative;
    right:660px ;
    text-align: center;
    color: red;
    font-family: fantasy;
}

.bside {
    color: green;
    margin-top: 10px;
    font-family: monospace;
}

.cside {
    color: #FFEE40;
    margin-top:10px;
    font-family: cursive;
}

.dside {
    color: #4380D3;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
}

.vine {
    position: relative;
    bottom: 100px;
    left: 5px;
}

.wiw {
    margin-top: 0px;
    text-align: left;
    position: relative;
    right: 247px;
}

.waw {
    margin-top: 100px;
    text-align: left;
    position: relative;
    right: 70px;
}

.wew {
    position: relative;
    right: 540px;
}

.vini {
    position: relative;
    bottom: 190px;
    left: 5px;
}

.blyat {
    float: left;
    position: relative;
    bottom:130px ;
}
.ten {
    position: relative;
    right: 540px;
}

