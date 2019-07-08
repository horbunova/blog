<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Style the body */
body {
  font-family: Arial;
  margin: 0;
}

/* Header/logo Title */
.header {
  font-family: URW Chancery L, cursive;
  padding: 30px;
  text-align: center;
  background: #1abc9c;
  color: white;
}

/* Style the top navigation bar */
.navbar {
  display: flex;
  background-color: #987;
}

/* Style the navigation bar links */
.navbar a {
  color: white;
  padding: 14px 20px;
  text-decoration: none;
  text-align: center;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #ddd;
  color: black;
}

/* Column container */
.row {  
  display: flex;
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {
  flex: 70%;
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row, .navbar {   
    flex-direction: column;
  }
}
</style>
</head>
<body>

<!-- Header -->
<div class="header">
  <h1>Tamara's travel blog</h1>
  <p>Enjoy the very moment</p>
</div>

<!-- Navigation Bar -->
<div class="navbar">
  <a href="#">дом ♥</a>
  <a href="#">кто я</a>
  <a href="#">связь</a>
</div>

<!-- The flexible grid (content) -->
<div class="row">
  <div class="main">
    <h2>в этот раз Львов</h2>
    <h5>May 12, 2019</h5>
    <div class="fakeimg" style="height:200px;"><img src="lviv.jpg" height="42" width="42"></div>
    <p>особенная атмосфера города, его дух и колорит покорил моё сердечко в этот раз. никогда раньше не проникалась Львовом, но в этот раз все было иначе.
<br><br>
уличные музыканты, невероятно вкусная и красивая еда, правильная компания и количество радостных лиц на улицах города обеспечили мне заряд энергии, настрой работать ещё больше и ещё лучше!
<br><br>
спасибо 🌸</p>
    <br>
    <h2>испанская неделя</h2>
    <h5>April 25, 2019</h5>
    <div class="fakeimg" style="height:200px;"><img src="spain.jpg" height="42" width="42"></div>    <p>а прогулки под дождём, палящим солнцем, а неправильно построенные маршруты предательским гуглом, а войны с билетными автоматами в метро, а нервы по мелочам, а литры испанского вина и килограммы мидий за "спасибо"??? а что ж это за путешествие без приключений?</p>
        <br>
        
    <h2>масёк, ты сможешь все</h2>
    <h5>December 1, 2019</h5>
    <div class="fakeimg" style="height:200px;"><img src="portugal.jpg" height="42" width="42"></div>
    <p>люблю свою зиму - она солнечная, тёплая и местами даже жаркая.
<br><br>
люблю свою целеустремленность, ведь если чего-то искренне хочу, знаю, что добьюсь.
<br><br>
я много чего люблю, а что люблю - то делаю. и всегда стараюсь делать хорошо, ведь иначе - смысл?
<br><br>
спасибо</p>

<br>
    <h2>на погнали в Хорватию автостопом?</h2>
    <h5>September 28, 2019</h5>
    <div class="fakeimg" style="height:200px;"><img src="zagreb.jpg" height="42" width="42"></div>
    <p>Привет, Загреб!
<br><br>
милый и уютный, просторный и свободный. Небольшие домашние магазинчики, почти игрушечные кафе, рестораны и бары, уютные парки — всё это делает Загреб весьма выделяющимся на фоне столиц других стран. даже сравнивая с Киевом - ну все равно, что юнит с ацептансом сравнивать;) 
<br><br>
Загреб – это Хорватия в миниатюре. здесь ты найдешь все, что любят и чем гордятся хорваты.
<br><br>
а ночью спокойный и уютный город оживает и меняется, а тусить хорваты умеют как никто другой - они даже фестивали бургеров устраивают!</p>

<br>
    <h2>все же о главном</h2>
    <h5>September 3, 2019</h5>
    <div class="fakeimg" style="height:200px;"><img src="split.jpg" height="42" width="42"></div>
    <p>я уже давно задумалась о целях своих поездок - когда не знаешь зачем, как-то сложнее сразу становится. смотреть на новые пейзажи? ну согласитесь, они же так схожи. собирать магнитики? ой, дальше. кушать? ладно, это было вполне очевидно:)
<br><br>
различать страны на вкус - вот чем бы я хотела заниматься. и дело вовсе не в еде - это не цель? это средство быть счастливым в той атмосфере, колорите, культуре! 
<br><br>
страны с богатой историей, разнообразной и вкусной кухней, открытыми людьми манят неимоверно, чего мне сопротивляться??!</p>
</div>
  <br>
  
  
  <div class="side">
    <h2>Кто я</h2>
    <h5>сначала фото</h5>
    <div class="fakeimg" style="height:200px;"><img src="me.jpg" height="42" width="42"></div>
    <p>вечный двигатель - вдохновляю сама себя</p>
    <h3>больше хлеба и зрелищ</h3>
    <p>линки</p>
    <div class="fakeimg" style="height:60px;"><img src="instalogo.png" height="42" width="42"></div><br>
    <div class="fakeimg" style="height:60px;"><img src="fblogo.png" height="42" width="42"></div><br>
    
</div>

<!-- Footer -->
<div class="footer">
  <h2>Footer</h2>
</div>

</body>
</html>

