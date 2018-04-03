# "El Sombrero" Mexican Restaurant
<!--Dev Project By Luis Ortiz-->
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
  </head>
<body>

<button class="tablink" onclick="openPage('Home', this, '#FFCA28')"id="defaultOpen">Home</button>
<button class="tablink" onclick="openPage('menu', this, '#FFCA28')" >Menu</button>
<button class="tablink" onclick="openPage('specialties', this, '#FFCA28')">Specialties "El Sombrero"</button>
<button class="tablink" onclick="openPage('special', this, '#FFCA28')">Special Menus</button>
<button class="tablink" onclick="openPage('speciald', this, '#FFCA28')">Special Days</button>
<button class="tablink" onclick="openPage('find', this, '#FFCA28')">Find Us</button>

  
  <!-- Home -->
  <!--Dev Project By Luis Ortiz-->
<div id="Home" class="tabcontent">
  <div class="header">
      <div class="container">
        <h1>"El Sombrero"</h1>
        <p>Mexican Restaurant</p>
      </div>
    </div>

    <div class="nav">
      <div class="container">
      
        <!--<ul>
    <li><strong>Home</strong></li>
    <li><a href="about.html">About Us</a></li>
    <li><a href="menu.html">Menu</a></li>
    <li><a href="specialties.html">Specialties "El Sombrero</a></li>
    <li><a href="special.html">Special Menus</a></li>
    <li><a href="find.html">Find Us</a></li>
        </ul>-->
      </div>
    </div>
    <div class="main">
      <div class="container">
        <img src="https://lh5.googleusercontent.com/-NuP51-nUCBc/WcBApoe6gNI/AAAAAAAAAVA/OrxNweTPZcsW1gPNi7Iu22QFUWEsLkTHACLIBGAYYCw/w284-h160-k-no/" height="128" width="196">
        <h2>Bienvenido!!</h2>
        <p>At "El Sombrero" mexican restaurant you can find and taste the most real and delicious mexican dishes on all the city.</p>
        <p> Plus, you can take a break into the mexican culture, while eating mexican food. </p>
        <p></p>
      </div>
    </div>

    <div class="jumbotron">
      <div class="container">
        <h2>Call Today</h2>
        <p>And Pick Up Your Order</p>
        <a class="btn" href="#">(731)-783-0079</path>
</svg></a>
      </div>
    </div>
    <div class="footer">
      <div class="container">
        <p>&copy;Dev Project by Luis Ortiz</p>
      </div>
    </div>
  <style>
/* If the screen size is 601px wide or more, set the font-size of <div> to 80px */
@media screen and (min-width: 601px) {
  div.example {
    font-size: 80px;
  }
}

/* If the screen size is 600px wide or less, set the font-size of <div> to 30px */
@media screen and (max-width: 600px) {
  div.example {
    font-size: 30px;
  }
}    
.menu-item {
  margin: 35px 0;
  font-size: 18px;
}
 
.menu-item-name{
  font-family: helvetica;
  font-weight: bold;
  border-bottom: 2px dotted rgb(213, 213, 213);
}
 
.menu-item-description {
  font-style: italic;
  font-size: .9em;
  line-height: 1.5em;
}
 
.menu-item-price{
  float: right;
  font-weight: bold;
  font-family: arial;
  margin-top: -22px;
}
.accordion {
    background-color: #eee;
    color: #444;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
    transition: 0.4s;
}

.active, .accordion:hover {
    background-color: #ccc; 
}

.panel {
    padding: 0 18px;
    display: none;
    background-color: white;
    overflow: hidden;
}    
    html, body {
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
}
h1 {
  color: black;
}

.container {
  margin: 0 auto;
  max-width: 940px; 
  padding: 0 10px;
  color: #00000;
}

.header {
  background: url(http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg) no-repeat center center; 
  background-size: cover;
  height: 800px;
  text-align: center; 
  text-color: black;
}
.logo {
  height: 80px;
  width: 80px;
  background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  background-size: contain;
  background-repeat: no-repeat;
  display: inline-block;
  position: relative;
  top: 1em;
}

.header .container {
  position: relative;
  top: 200px;
}

.header h1 {
  color: black;
  line-height: 100px; 
  font-size: 80px;
  margin-top: 0;
  margin-bottom: 80px;
  text-transform: uppercase; 
}

@media (min-width:850px) {
  .header h1 {
    font-size: 120px;
  }
}

.header p {
  color: black;
  font-weight: 500;
  letter-spacing: 8px;
  margin-bottom: 40px;
  margin-top: 0;
  text-transform: uppercase; 
  font-size: 50px;
}

.btn {
  color: #fff;
  background: #000;
  padding: 10px 40px;
  text-decoration: none; 
  transition: background .5s; 
}

    .nav { 
  background: #000;
  height: 10px; 
  width: 100%;
}

.nav ul {
  height: 80px;
  list-style: none;
  margin: 0 auto; 
  padding: 0;
}

.nav ul li {
  color: #fff;
  display: inline-block; 
  height: 80px;
  line-height: 80px; 
  list-style: none;
  padding: 0 19px;
  transition: background .5s; 
}

.btn:hover, .nav ul li:hover {
  background: #117bff;
  cursor: pointer; 
  transition: background .5s;  
}
    
    
    

.main .container {
  margin: 80px auto;
}

.main img {
  float: left;
  margin: 50px 80px 50px 0;
}

.jumbotron {
  background: url(http://www.lacasadesamuel.com/imgs/desconocidojeje.jpg) center center;
  background-size: cover;
  height: 600px; 
}

.jumbotron .container {
  position: relative;
  top: 220px;
}

.jumbotron h2 {
  color: black;
  text-align: right; 
  font-size: 45px;
}

.jumbotron p {
  color: black; 
  text-align: right; 
  font-size: 25px;
}

.jumbotron .btn {
  margin: 10px 0 0;
  float: right; 
  font-size: 20px;
}

.footer { 
  background: #000;
  height: 80px;
}

.footer p { 
  color: #fff;
  font-size: 14px;  
  height: 80px; 
  line-height: 80px;
  margin: 0;  
}

@media (max-width: 500px) {
  .header h1 {
    font-size: 50px;
    line-height: 64px;
  }

  .main, .jumbotron {
    padding: 0 30px;
  }

  .main img {
    width: 100%;
  }
 @media only screen and (max-width: 1500px) {
  .page-title {
    width: 800px;
  }
}

@media only screen and (min-width: 320px) and (max-width: 1500px) {
  .gallery-item .thumbnail {
    width: 95%;
  }
}

@media only screen and (min-resolution: 150dpi) {
  .logo {
    background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  }
}

@media only screen and (max-resolution: 150dpi) and (max-width: 1500px) {
  .page-description {
    font-size: 20px;
  }
}
  @media only screen and (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
    /* CSS ruleset */
}
  @media only screen and (min-resolution: 150dpi)
    .nav
    .container
  </style>
  </div>

      <!-- Menu -->
<!--Dev Project By Luis Ortiz-->
<div id="menu" class="tabcontent">
  <div class="header">
      <div class="container">
        <h1>"El Sombrero"</h1>
        <p>Menu</p>
      </div>
    </div>

    <div class="nav">
      <div class="container">
        <!--<ul>
    <li><strong>Home</strong></li>
    <li><a href="about.html">About Us</a></li>
    <li><a href="menu.html">Menu</a></li>
    <li><a href="specialties.html">Specialties "El Sombrero</a></li>
    <li><a href="special.html">Special Menus</a></li>
    <li><a href="find.html">Find Us</a></li>
        </ul>-->
      </div>
    </div>
    <div class="main">
      <div class="container">
        <!--<img src="https://lh5.googleusercontent.com/-NuP51-nUCBc/WcBApoe6gNI/AAAAAAAAAVA/OrxNweTPZcsW1gPNi7Iu22QFUWEsLkTHACLIBGAYYCw/w284-h160-k-no/" height="128" width="196">-->
        <h2>Menu</h2>

<button class="accordion"><strong>Appetizers</strong></button>
<div class="panel">
  <div class="menu-item">
         <div class="menu-item-name">
            Cheese Dip
         </div>
         <div class="menu-item-price">
            $3.00
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Bean Dip
         </div>
         <div class="menu-item-price">
            $2.75
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Guacamole Dip
         </div>
         <div class="menu-item-price">
            $3.00
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Queso Con Carne Dip
         </div>
         <div class="menu-item-price">
            $4.00
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Spinach Dip
         </div>
         <div class="menu-item-price">
            $3.00
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chipotle Dip
         </div>
         <div class="menu-item-price">
            $3.00
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Choriqueso Dip
         </div>
         <div class="menu-item-price">
            $4.00
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Queso Fundido
         </div>
         <div class="menu-item-price">
            $6.50
         </div>
         <div class="menu-item-description">
            Melted cheese topped with sauteed oninon, bell pepper, tomato and chorizo. Brought to you on a hot skillet and served with tortillas.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Mexican Chili
         </div>
         <div class="menu-item-price">
            $3.50
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chicken Wings
         </div>
         <div class="menu-item-price">
            $5.99
         </div>
         <div class="menu-item-description">
            Comes with 8 pieces
         </div>
      </div>
</div>

<button class="accordion"><strong>Nachos</strong></button>
<div class="panel">
<p>Shredded chicken is cooked with onion, bell pepper, and tomato
  <div class="menu-item">
         <div class="menu-item-name">
            Cheese and Chicken
         </div>
         <div class="menu-item-price">
            $5.25
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           1/2 Order
         </div>
         <div class="menu-item-price">
            $3.75
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Cheese and Beef
         </div>
         <div class="menu-item-price">
            $4.75
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            1/2 Order
         </div>
         <div class="menu-item-price">
            $3.25
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Cheese and Beans
         </div>
         <div class="menu-item-price">
            $4.25
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            1/2 Order
         </div>
         <div class="menu-item-price">
            $3.00
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Cheese Only
         </div>
         <div class="menu-item-price">
            $4.00
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            1/2 Order
         </div>
         <div class="menu-item-price">
            $2.75
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Nachos El Sombrero
         </div>
         <div class="menu-item-price">
            $7.99
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            1/2 Order
         </div>
         <div class="menu-item-price">
            $5.00
         </div>
         <div class="menu-item-description">
            Crispy tortilla chips topped with beans, chicken, beef, lettuce, tomatoes, cheese, and sour cream.
         </div>
      </div>
      <p><strong>Nachos Fajita</strong></p>
      <p>(cooked with onion, bell pepper, and tomato)
      <div class="menu-item">
         <div class="menu-item-name">
            Chicken or Steak
         </div>
         <div class="menu-item-price">
            $8.25
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           1/2 Order
         </div>
         <div class="menu-item-price">
            $6.00
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Shrimp
         </div>
         <div class="menu-item-price">
            $8.99
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            1/2 Order
         </div>
         <div class="menu-item-price">
            $6.00
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chicken, Steak, and Shrimp
         </div>
         <div class="menu-item-price">
            $9.99
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            1/2 Order
         </div>
         <div class="menu-item-price">
            $7.50
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Nachos Jalisco
         </div>
         <div class="menu-item-price">
            $10.99
         </div>
         <div class="menu-item-description">
            Chicken, steak, and srimp cooked with onion, bell pepper and tomato. Covered with lettuce, pico de gallo, and guacamole.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Nachos Chipotle
         </div>
         <div class="menu-item-price">
            $7.99
         </div>
         <div class="menu-item-description">
            Chips topped with chipotle cheese dip, grilled chicken, chorizo, sauteed onions and sour cream.
         </div>
      </div>
</div>

<button class="accordion"><strong>Salads And Soup</strong></button>
<div class="panel">
  <p>Shredded chicken is cooked with onion, bell pepper, and tomato</p>
  <div class="menu-item">
         <div class="menu-item-name">
            Taco Salad
         </div>
         <div class="menu-item-price">
            $7.25
         </div>
         <div class="menu-item-description">
           A crispy flour tortilla with melted cheese sauce, topped with ground beef or shredded chicken, lettuce, tomato, sour cream, guacamole, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Taco Salad Fajita
         </div>
         <div class="menu-item-price">
            $8.25
         </div>
         <div class="menu-item-description">
           A crispy flour tortilla with melted cheese sauce, topped with your choice of chicken or steak cooked with onion, bell pepper, and tomato. Covered with lettuce, tomato, guacamole, sour cream, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Shrimp Taco Salad
         </div>
         <div class="menu-item-price">
            $8.99
         </div>
         <div class="menu-item-description">
            A crispy flour tortilla with melted cheese sauce, topped with shrimp cooked with onion, bell pepper, and tomato. Covered with lettuce, sour cream, guacamole, tomato, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Taco Salad El Sombrero
         </div>
         <div class="menu-item-price">
            $9.99
         </div>
         <div class="menu-item-description">
            Chicken, steak, and shrimp sauteed with onions, bell peppers , tomato, and mushrooms. Covered with lettuce, sour cream, guacamole, tomato, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Grilled Chicken Salad
         </div>
         <div class="menu-item-price">
            $5.75
         </div>
         <div class="menu-item-description">
            Lettuce, onions, bell pepper, and tomato. Topped with grilled chicken, sauteed mushrooms, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            add shrimp
         </div>
         <div class="menu-item-price">
            $2.00
         </div>
         <div class="menu-item-description">
            <!--Dev Project By Luis Ortiz-->
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            House Salad
         </div>
         <div class="menu-item-price">
            $3.50
         </div>
         <div class="menu-item-description">
            Lettuce, pico de gallo, jalapeno, shredded cheese, and sliced avocado. 
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Tossed Salad
         </div>
         <div class="menu-item-price">
            $3.25
         </div>
         <div class="menu-item-description">
            Lettuce, onion, pepper bell, tomato, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Guacamole Salad
         </div>
         <div class="menu-item-price">
            $3.50
         </div>
         <div class="menu-item-description">
            Lettuce, tomato, shredded cheese, and guacamole.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Cup
         </div>
         <div class="menu-item-price">
            $4.25
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Bowl
         </div>
         <div class="menu-item-price">
            $5.25
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
</div>
<button class="accordion"><strong>Burritos And Enchiladas</strong></button>
<div class="panel">
<p>Shredded chicken is cooked with onion, bell pepper, and tomato.<br>-add cheese sauce for $0.75<br>-substitute grilled chicken or steak for $1.00</p>
<div class="menu-item">
         <div class="menu-item-name">
            Burrito Special
         </div>
         <div class="menu-item-price">
            $5.99
         </div>
         <div class="menu-item-description">
           A flour tortilla stuffed with ground beef or shredded chicken. Topped with red sauce, lettuce, sour cream, tomato, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Burrito Mexicano
         </div>
         <div class="menu-item-price">
            $6.75
         </div>
         <div class="menu-item-description">
           Flour tortilla stuffed with pork that is cooked with onion, and bell pepper. Topped with red sauce, cheese sauce, lettuce, tomato, and sliced avocado.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Burrito El Sombrero 
         </div>
         <div class="menu-item-price">
            $7.75
         </div>
         <div class="menu-item-description">
            A flour tortilla stuffed with ground beef or shredded chicken. Topped with red sauce, lettuce, sour cream, tomato, and shredded cheese. Served with mexican rice, refried beans, lettuce, sour cream, and tomato.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Burrito De Carne Asada
         </div>
         <div class="menu-item-price">
            $7.99
         </div>
         <div class="menu-item-description">
            A flour tortilla stuffed with slices of steak, topped with red sauce, lettuce, guacamole, and pico de gallo. Served with mexican rice and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Burrito Verde
         </div>
         <div class="menu-item-price">
            $6.99
         </div>
         <div class="menu-item-description">
            A flour tortilla stuffed with grilled chicken, cooked with onion, topped with green sauce. Served with mexican rice, lettuce, sour cream, and tomato.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Burrito Tapatio 
         </div>
         <div class="menu-item-price">
            $8.99
         </div>
         <div class="menu-item-description">
            A big burrito stuffed with chicken or steak, lettuce, refried beans, sour cream, guacamole, and shredded cheese, covered with cheese sauce.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Burrito Yucatan
         </div>
         <div class="menu-item-price">
            $9.99
         </div>
         <div class="menu-item-description">
            A big burrito stuffed with chicken, steak, and shrimp sauteed with onion, tomato, bell pepper, and mushrooms. Covered with red sauce and cheese sauce.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Enchiladas Supremas
         </div>
         <div class="menu-item-price">
            $7.99
         </div>
         <div class="menu-item-description">
            Four rolled corn tortillas, one beef, one shredded chicken, one bean, and one cheese, topped with enchilada sauce, lettuce, sour cream, tomato, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Enchiladas Rancheras
         </div>
         <div class="menu-item-price">
            $6.75
         </div>
         <div class="menu-item-description">
            Two cheese enchiladas topped with cooked pork with tomato, onion, and bell pepper, and enchilada sauce. Served with lettuce, sour cream, guacamole, and pico de gallo.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Sombrero Special
         </div>
         <div class="menu-item-price">
            $7.25
         </div>
         <div class="menu-item-description">
            One chicken burrito and one chicken enchilada topped with enchilada sauce, lettuce, shredded cheese, sour cream, pico de gallo, and sliced avocado.
         </div>
      </div>
</div>
<button class="accordion"><strong>Quesadillas</strong></button>
<div class="panel">
<p>Shredded chicken is cooked with bell pepper, and tomato.<br> -add cheese sauce for $0.75</p>
<div class="menu-item">
         <div class="menu-item-name">
            Quesadilla (cheese only)
         </div>
         <div class="menu-item-price">
            $2.99
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Quesadilla Rellena
         </div>
         <div class="menu-item-price">
            $6.50
         </div>
         <div class="menu-item-description">
           A cheese quesadilla stuffed with chunks of beef or shredded chicken and beans. served with lettuce, sour cream, and tomato.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            1/2 Order
         </div>
         <div class="menu-item-price">
            $4.25
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Fajita Quesadilla
         </div>
         <div class="menu-item-price">
            $7.50
         </div>
         <div class="menu-item-description">
            A cheese quesadilla stuffed with steak or chicken that is sauteed with onion, bell pepper, and tomato. Served with lettuce, sour cream, and tomato.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            1/2 Order
         </div>
         <div class="menu-item-price">
            $5.75
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Shrimp Quesadilla
         </div>
         <div class="menu-item-price">
            $8.50
         </div>
         <div class="menu-item-description">
            A cheese quesadilla stuffed with shrimp that is sauteed with onion, bell pepper, and tomato. Served with lettuce, sour cream, and tomato.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            1/2 Order
         </div>
         <div class="menu-item-price">
            $6.25
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Garden Quesadilla
         </div>
         <div class="menu-item-price">
            $6.50
         </div>
         <div class="menu-item-description">
           A cheese quesadilla stuffed with onion, bell pepper, and tomato. Served with lettuce, sour cream, and tomato.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           1/2 Order
         </div>
         <div class="menu-item-price">
            $4.25
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Spinach and Mushroom Quesadilla
         </div>
         <div class="menu-item-price">
            $6.25
         </div>
         <div class="menu-item-description">
            A cheese quesadilla stuffed with spinach and mushrooms. Served with lettuce, sour cream, guacamole, and pico de gallo.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            1/2 Order
         </div>
         <div class="menu-item-price">
            $4.15
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Quesadilla El Sombrero
         </div>
         <div class="menu-item-price">
            $9.99
         </div>
         <div class="menu-item-description">
            A cheese quesadilla stuffed with chicken, steak, and shrimp sauteed onion, bell pepper, and tomato. Served with mexican rice covered with cheese sauce.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Quesadilla Especial
         </div>
         <div class="menu-item-price">
            $7.99
         </div>
         <div class="menu-item-description">
            Half of a chicken or steak quesadilla with sauteed onion, pepper bell, and tomato. Served with mexican rice, refried beans, lettuce, cream, and tomato.
         </div>
      </div>
</div>
<button class="accordion"><strong>Fajitas</strong></button>
<div class="panel">
<div class="menu-item">
         <div class="menu-item-name">
            Chicken or Steak
         </div>
         <div class="menu-item-price">
            $9.99
         </div>
         <div class="menu-item-description">
           Double.............$18.99
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Shrimp
         </div>
         <div class="menu-item-price">
            $11.99
         </div>
         <div class="menu-item-description">
           Double.............$21.99
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Fajitas Bravas
         </div>
         <div class="menu-item-price">
            $10.99
         </div>
         <div class="menu-item-description">
            Double.............$18.99<br>Tender strips of steak, chicken, and shrimp sauteed with onion, bell pepper, and tomato. Served with mexican rice, refried beans lettuce, sour cream, guacamole, and pico de gallo.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Fajitas El Sombrero
         </div>
         <div class="menu-item-price">
            $12.99
         </div>
         <div class="menu-item-description">
            Tender strips of steak, chicken, shrimp and chorizo sauteed with onion, tomato and mushrooms, covered with cheese sauce. Served with mexican rice, refried beans, lettuce, sour cream, and guacamole.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Fajitas Rancheras
         </div>
         <div class="menu-item-price">
            $9.99
         </div>
         <div class="menu-item-description">
            Tender strips of steak with sauteed onions. Topped with whole beans and hot ranchero sauce. Served with mexican rice, lettuce, sour cream, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Papa El Sombrero
         </div>
         <div class="menu-item-price">
            
         </div>
         <div class="menu-item-description">
            A baked potato topped with chicken, steak or shrimp with sauteed onion, bell pepper, tomato, and cheese sauce. Covered with lettuce sour cream, and shredded cheese.<br>Chicken or Steak...............$7.25<br>Shrimp...............................$8.25
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Parrillada Mexicana
         </div>
         <div class="menu-item-price">
            $24.99
         </div>
         <div class="menu-item-description">
            A sizzling platter of tender marinated steak, chicken, pork, and chorizo with sauteed onion, bell pepper, and tomato. Served with mexican rice, refried beans, lettuce, sour cream, guacamole, pico de gallo, and two cheese quesadillas. Serves 2-4<br>Add shrimp ......................................$27.99<br>Molcajete ........................................$12.99<br>With Shrimp and Chorizo................$14.99 <br>(Grilled chicken and steak with sauteed onion, bell pepper and tomato topped with whole beans and your choice of green or tomatillo sauce garnished with cambray, onions, cacus leaf and banana pepper served with rice, lettuce, guacomole, pico degallo and sour cream)
         </div>
      </div>     
</div>
<button class="accordion"><strong>A La Carte</strong></button>
<div class="panel">
<p>Shredded chicken is cooked with onion, bell pepper, and tomato.<br>-add cheese sauce for $0.75</p>
<div class="menu-item">
         <div class="menu-item-name">
            Chile Con Queso
         </div>
         <div class="menu-item-price">
            $3.35
         </div>
         <div class="menu-item-description">
           Double.......................$6.25
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Beef Burrito
         </div>
         <div class="menu-item-price">
            $3.25
         </div>
         <div class="menu-item-description">
           Double.......................$6.25
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chicken Burrito
         </div>
         <div class="menu-item-price">
            $3.75
         </div>
         <div class="menu-item-description">
            Double.......................$6.50
         </div>
      </div>
  <!--Dev Project By Luis Ortiz-->
      <div class="menu-item">
         <div class="menu-item-name">
            Bean Burrito
         </div>
         <div class="menu-item-price">
            $3.00
         </div>
         <div class="menu-item-description">
            Double.......................$5.75
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Grilled Chicken or Steak Burrito
         </div>
         <div class="menu-item-price">
            $4.50
         </div>
         <div class="menu-item-description">
            Double.......................$8.00
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Shrimp Burrito
         </div>
         <div class="menu-item-price">
            $5.50
         </div>
         <div class="menu-item-description">
            Double.......................$9.50
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Cheese Burrito
         </div>
         <div class="menu-item-price">
            $3.75
         </div>
         <div class="menu-item-description">
            Double.......................$6.50
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Enchiladas
         </div>
         <div class="menu-item-price">
            $1.99
         </div>
         <div class="menu-item-description">
            Triple.........................$5.25<br>(Beef, chicken, cheese or bean)
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Beef Taco
         </div>
         <div class="menu-item-price">
            $1.50
         </div>
         <div class="menu-item-description">
            Triple.........................$4.25<br>(Hard or soft shell)
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chicken Taco
         </div>
         <div class="menu-item-price">
            $1.65
         </div>
         <div class="menu-item-description">
            Triple.........................$4.50<br>(Hard or soft shell)
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Grilled Chicken or Steak Taco
         </div>
         <div class="menu-item-price">
            $2.50
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Tamale
         </div>
         <div class="menu-item-price">
            $2.00
         </div>
         <div class="menu-item-description">
            Triple.........................$5.50
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chile Relleno
         </div>
         <div class="menu-item-price">
            $3.25
         </div>
         <div class="menu-item-description">
            Double.......................$6.00
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chalupa
         </div>
         <div class="menu-item-price">
            $3.25
         </div>
         <div class="menu-item-description">
            Double.......................$6.00
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Beef Tostada
         </div>
         <div class="menu-item-price">
            $3.75
         </div>
         <div class="menu-item-description">
            Double.......................$7.00
         </div>
      </div>
</div>
<!--<button class="accordion">Combinations</button>
<div class="panel">
</div>
<button class="accordion">Side Orders</button>
<div class="panel">
</div>
<button class="accordion">Desserts</button>
<div class="panel">
</div>-->
<button class="accordion"><strong>Beverages</strong></button>
<div class="panel">
<p>Free refills on soft drinks, coffee, and iced tea.<br>-carryout cups for $0.50</p>
<div class="menu-item">
         <div class="menu-item-name">
            Mexican Beer
         </div>
         <div class="menu-item-price">
            $3.25
         </div>
         <div class="menu-item-description">
           <!--Dev Project By Luis Ortiz-->
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           American Beer
         </div>
         <div class="menu-item-price">
            $2.25
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Soft Drinks
         </div>
         <div class="menu-item-price">
            $1.75
         </div>
         <div class="menu-item-description">
            Coke, Diet Coke, Sprite, Dr.Pepper, Pink Lemonade.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Iced Tea
         </div>
         <div class="menu-item-price">
            $1.50
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Coffee
         </div>
         <div class="menu-item-price">
            $1.25
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Milk
         </div>
         <div class="menu-item-price">
            $1.25
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>     
</div>
      </div>
    </div>

    <!--<div class="jumbotron">
      <div class="container">
        <h2>Call Us Today</h2>
        <p>Order Your Favorite Mexican Food.</p>
        <a class="btn" href="#">CALL NOW</path>
</svg></a>
      </div>
    </div>-->

    <div class="footer">
      <div class="container">
        <p>&copy;Dev Project by Luis Ortiz</p>
      </div>
    </div>
  <style> 
/* If the screen size is 601px wide or more, set the font-size of <div> to 80px */
@media screen and (min-width: 601px) {
  div.example {
    font-size: 80px;
  }
}

/* If the screen size is 600px wide or less, set the font-size of <div> to 30px */
@media screen and (max-width: 600px) {
  div.example {
    font-size: 30px;
  }
}        
    html, body {
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
}
h1 {
  color: black;
}

.container {
  margin: 0 auto;
  max-width: 940px; 
  padding: 0 10px;
  color: #00000;
}

.header {
  background: url(https://imgur.com/NxI5kpJ) no-repeat center center; 
  background-size: cover;
  height: 800px;
  text-align: center; 
  text-color: black;
}
.logo {
  height: 80px;
  width: 80px;
  background-image: url("https://imgur.com/NxI5kpJ");
  background-size: contain;
  background-repeat: no-repeat;
  display: inline-block;
  position: relative;
  top: 1em;
}

.header .container {
  position: relative;
  top: 200px;
}

.header h1 {
  color: black;
  line-height: 100px; 
  font-size: 80px;
  margin-top: 0;
  margin-bottom: 80px;
  text-transform: uppercase; 
}

@media (min-width:850px) {
  .header h1 {
    font-size: 120px;
  }
}

.header p {
  color: black;
  font-weight: 500;
  letter-spacing: 8px;
  margin-bottom: 40px;
  margin-top: 0;
  text-transform: uppercase; 
  font-size: 50px;
}

.btn {
  color: #fff;
  background: #000;
  padding: 10px 40px;
  text-decoration: none; 
  transition: background .5s; 
}

    .nav { 
  background: #000;
  height: 10px; 
  width: 100%;
}

.nav ul {
  height: 80px;
  list-style: none;
  margin: 0 auto; 
  padding: 0;
}

.nav ul li {
  color: #fff;
  display: inline-block; 
  height: 80px;
  line-height: 80px; 
  list-style: none;
  padding: 0 19px;
  transition: background .5s; 
}

.btn:hover, .nav ul li:hover {
  background: #117bff;
  cursor: pointer; 
  transition: background .5s;  
}
    
    
    

.main .container {
  margin: 80px auto;
}

.main img {
  float: left;
  margin: 50px 80px 50px 0;
}

.jumbotron {
  background: url(http://www.lacasadesamuel.com/imgs/desconocidojeje.jpg) center center;
  background-size: cover;
  height: 600px; 
}

.jumbotron .container {
  position: relative;
  top: 220px;
}

.jumbotron h2 {
  color: black;
  text-align: right; 
  font-size: 45px;
}

.jumbotron p {
  color: black; 
  text-align: right; 
  font-size: 25px;
}

.jumbotron .btn {
  margin: 10px 0 0;
  float: right; 
  font-size: 20px;
}

.footer { 
  background: #000;
  height: 80px;
}

.footer p { 
  color: #fff;
  font-size: 14px;  
  height: 80px; 
  line-height: 80px;
  margin: 0;  
}

@media (max-width: 500px) {
  .header h1 {
    font-size: 50px;
    line-height: 64px;
  }

  .main, .jumbotron {
    padding: 0 30px;
  }

  .main img {
    width: 100%;
  }
 @media only screen and (max-width: 1500px) {
  .page-title {
    width: 800px;
  }
}

@media only screen and (min-width: 320px) and (max-width: 1500px) {
  .gallery-item .thumbnail {
    width: 95%;
  }
}

@media only screen and (min-resolution: 150dpi) {
  .logo {
    background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  }
}

@media only screen and (max-resolution: 150dpi) and (max-width: 1500px) {
  .page-description {
    font-size: 20px;
  }
}
  @media only screen and (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
    /* CSS ruleset */
}
  @media only screen and (min-resolution: 150dpi)
    .nav
    .container
  </style>
  <script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
    acc[i].addEventListener("click", function() {
        this.classList.toggle("active");
        var panel = this.nextElementSibling;
        if (panel.style.display === "block") {
            panel.style.display = "none";
        } else {
            panel.style.display = "block";
        }
    });
}
</script>
  </div>

      <!-- Specialties "El Sombrero" -->
<!--Dev Project By Luis Ortiz-->
<div id="specialties" class="tabcontent">
  <div class="header">
      <div class="container">
        <h1>"El Sombrero"</h1>
        <p>Specialties "El Sombrero"</p>
      </div>
    </div>

    <div class="nav">
      <div class="container">
        <!--<ul>
    <li><strong>Home</strong></li>
    <li><a href="about.html">About Us</a></li>
    <li><a href="menu.html">Menu</a></li>
    <li><a href="specialties.html">Specialties "El Sombrero</a></li>
    <li><a href="special.html">Special Menus</a></li>
    <li><a href="find.html">Find Us</a></li>
        </ul>-->
      </div>
    </div>
    <div class="main">
      <div class="container">
        <!--<img src="https://lh5.googleusercontent.com/-NuP51-nUCBc/WcBApoe6gNI/AAAAAAAAAVA/OrxNweTPZcsW1gPNi7Iu22QFUWEsLkTHACLIBGAYYCw/w284-h160-k-no/" height="128" width="196">-->

      </div>
    </div>
<h2 class="menu-section-title">Especialidades El Sombrero</h2>
     <p>Shredded chicken is cooked with onion, bell pepper and tomato.</p>
      <div class="menu-item">
         <div class="menu-item-name">
           Carne Asada
         </div>
         <div class="menu-item-price">
            $8.99
         </div>
         <div class="menu-item-description">
           Skirt steak served with mexican rice, refried beans, lettuce, tomato, onion, avocado, and jalapenos.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Carnitas
         </div>
         <div class="menu-item-price">
            $8.99
         </div>
         <div class="menu-item-description">
            Pork tips served with mexican rice, refried beans, lettuce, tomato, onion, avocado, and jalapenos
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chile Colorado
         </div>
         <div class="menu-item-price">
            $8.99
         </div>
         <div class="menu-item-description">
            Tender strips of steak cooked with hot ranchero sauce. Served with mexican and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Tacos De Carne Asada
         </div>
         <div class="menu-item-price">
            $8.99
         </div>
         <div class="menu-item-description">
            Three corn of flour tortillas stuffed with steak. Served with pico de gallo, refried beans and tomatillo sauce.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Steak Mexicano
         </div>
         <div class="menu-item-price">
            $10.99
         </div>
         <div class="menu-item-description">
            T-bone steak topped with cooked onion, bell pepper, and tomado. Served with mexican rice and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Steak Tampiquena
         </div>
         <div class="menu-item-price">
            $10.99
         </div>
         <div class="menu-item-description">
            T-bone steak served with mexican rice, refried beans and tossed salad.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Steak Ranchero
         </div>
         <div class="menu-item-price">
            $10.99
         </div>
         <div class="menu-item-description">
            T-bone steak covered with hot ranchero sauce. Served with mexican rice and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            T-bone Steak
         </div>
         <div class="menu-item-price">
            $12.99
         </div>
         <div class="menu-item-description">
            A grilled t-bone steak served with mexican rice, grilled vegetables covered with cheese and your choice of a baked potato with butter and sour cream, french fries, a tossed salad.
         </div>
      </div>
  <!--Dev Project By Luis Ortiz-->
      <div class="menu-item">
         <div class="menu-item-name">
            Steak Acapulco
         </div>
         <div class="menu-item-price">
            $12.99
         </div>
         <div class="menu-item-description">
            A grilled t-bone steak topped with sauteed onion, bell pepper, tomato and shrimp. Served with mexican rice and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Camarones a La Diabla
         </div>
         <div class="menu-item-price">
            $7.99
         </div>
         <div class="menu-item-description">
           Grilled shrimp cooked with hot ranchero sauce on top of bed of rice with cheese sauce, lettuce, onion, and bell pepper.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Shrimp El Sombrero
         </div>
         <div class="menu-item-price">
            $8.99
         </div>
         <div class="menu-item-description">
            Sauteed shrimp with onion, bell peppers, tomato, and mushrooms on a bed of cheese. Served with lettuce, guacamole, pico de gallo, sour cream, and your choice of mexican rice or refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chicken Flautas 
         </div>
         <div class="menu-item-price">
            $6.99
         </div>
         <div class="menu-item-description">
            Five rolled corn tortillas stuffed with shredded chicken. Topped with lettuce, shredded cheese, tomato, sour cream and avocado. Served with a special sauce.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Xochimilco 
         </div>
         <div class="menu-item-price">
            $8.50
         </div>
         <div class="menu-item-description">
            Two grilled chicken burritos topped with sour cream sauce and four chicken flautas. Served with mexican rice, lettuce, tomato, and cheese sauce.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Pollo El Sombrero
         </div>
         <div class="menu-item-price">
            $8.25
         </div>
         <div class="menu-item-description">
            A grilled chicken breast topped with sauteed onion, bell pepper, tomato, and cheese. Served with mexican rice, lettuce, pico de gallo and sliced avocado.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Spicy Chicken Chipotle
         </div>
         <div class="menu-item-price">
            $9.99
         </div>
         <div class="menu-item-description">
            A grilled chicken breast covered with a spicy chipotle sauce, a side of steamed vegetables and a baked potato with butter and sour cream.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Pollo Loco
         </div>
         <div class="menu-item-price">
            $6.25
         </div>
         <div class="menu-item-description">
            Mexican rice covered with cheese sauce and grilled chicken.<br>Large Order.....................$7.99
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Fiesta Dinner
         </div>
         <div class="menu-item-price">
            $10.99
         </div>
         <div class="menu-item-description">
            This platter has a little everything. A chalupa, taco, chile relleno, tamale, enchilada, mexican rice and refried beans.
         </div>
      </div>
    <!--<div class="jumbotron">
      <div class="container">
        <h2>Call Us Today</h2>
        <p>Order Your Favorite Mexican Food.</p>
        <a class="btn" href="#">CALL NOW</path>
</svg></a>
      </div>
    </div>-->

    <div class="footer">
      <div class="container">
        <p>&copy;Dev Project by Luis Ortiz</p>
      </div>
    </div>
  <style>
/* If the screen size is 601px wide or more, set the font-size of <div> to 80px */
@media screen and (min-width: 601px) {
  div.example {
    font-size: 80px;
  }
}

/* If the screen size is 600px wide or less, set the font-size of <div> to 30px */
@media screen and (max-width: 600px) {
  div.example {
    font-size: 30px;
  }
}        
    html, body {
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
}
h1 {
  color: black;
}

.container {
  margin: 0 auto;
  max-width: 940px; 
  padding: 0 10px;
  color: #00000;
}

.header {
  background: url(http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg) no-repeat center center; 
  background-size: cover;
  height: 800px;
  text-align: center; 
  text-color: black;
}
.logo {
  height: 8px;
  width: 80px;
  background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  background-size: contain;
  background-repeat: no-repeat;
  display: inline-block;
  position: relative;
  top: 1em;
}

.header .container {
  position: relative;
  top: 200px;
}

.header h1 {
  color: black;
  line-height: 100px; 
  font-size: 80px;
  margin-top: 0;
  margin-bottom: 80px;
  text-transform: uppercase; 
}

@media (min-width:850px) {
  .header h1 {
    font-size: 120px;
  }
}

.header p {
  color: black;
  font-weight: 500;
  letter-spacing: 8px;
  margin-bottom: 40px;
  margin-top: 0;
  text-transform: uppercase; 
  font-size: 50px;
}

.btn {
  color: #fff;
  background: #000;
  padding: 10px 40px;
  text-decoration: none; 
  transition: background .5s; 
}

    .nav { 
  background: #000;
  height: 10px; 
  width: 100%;
}

.nav ul {
  height: 80px;
  list-style: none;
  margin: 0 auto; 
  padding: 0;
}

.nav ul li {
  color: #fff;
  display: inline-block; 
  height: 80px;
  line-height: 80px; 
  list-style: none;
  padding: 0 19px;
  transition: background .5s; 
}

.btn:hover, .nav ul li:hover {
  background: #117bff;
  cursor: pointer; 
  transition: background .5s;  
}
    
    
    

.main .container {
  margin: 80px auto;
}

.main img {
  float: left;
  margin: 50px 80px 50px 0;
}

.jumbotron {
  background: url(http://www.lacasadesamuel.com/imgs/desconocidojeje.jpg) center center;
  background-size: cover;
  height: 600px; 
}

.jumbotron .container {
  position: relative;
  top: 220px;
}

.jumbotron h2 {
  color: black;
  text-align: right; 
  font-size: 45px;
}

.jumbotron p {
  color: black; 
  text-align: right; 
  font-size: 25px;
}

.jumbotron .btn {
  margin: 10px 0 0;
  float: right; 
  font-size: 20px;
}

.footer { 
  background: #000;
  height: 80px;
}

.footer p { 
  color: #fff;
  font-size: 14px;  
  height: 80px; 
  line-height: 80px;
  margin: 0;  
}

@media (max-width: 500px) {
  .header h1 {
    font-size: 50px;
    line-height: 64px;
  }

  .main, .jumbotron {
    padding: 0 30px;
  }

  .main img {
    width: 100%;
  }
 @media only screen and (max-width: 1500px) {
  .page-title {
    width: 800px;
  }
}

@media only screen and (min-width: 320px) and (max-width: 1500px) {
  .gallery-item .thumbnail {
    width: 95%;
  }
}

@media only screen and (min-resolution: 150dpi) {
  .logo {
    background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  }
}

@media only screen and (max-resolution: 150dpi) and (max-width: 1500px) {
  .page-description {
    font-size: 20px;
  }
}
  @media only screen and (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
    /* CSS ruleset */
}
  @media only screen and (min-resolution: 150dpi)
    .nav
    .container
  </style>
  </div>

      <!-- Special Menus -->
<!--Dev Project By Luis Ortiz-->
<div id="special" class="tabcontent">
  <div class="header">
      <div class="container">
        <h1>"El Sombrero"</h1>
        <p>Special Menus</p>
      </div>
    </div>

    <div class="nav">
      <div class="container">
        <!--<ul>
    <li><strong>Home</strong></li>
    <li><a href="about.html">About Us</a></li>
    <li><a href="menu.html">Menu</a></li>
    <li><a href="specialties.html">Specialties "El Sombrero</a></li>
    <li><a href="special.html">Special Menus</a></li>
    <li><a href="find.html">Find Us</a></li>
        </ul>-->
      </div>
    </div>
    <div class="main">
      <div class="container">
        <!--<img src="https://lh5.googleusercontent.com/-NuP51-nUCBc/WcBApoe6gNI/AAAAAAAAAVA/OrxNweTPZcsW1gPNi7Iu22QFUWEsLkTHACLIBGAYYCw/w284-h160-k-no/" height="128" width="196">-->
        
      </div>
    </div>
<h2 class="menu-section-title">Lunch Menu</h2>
     <p>Served everyday from 11:00 a.m. to 3:00 p.m. only.<br>-shredded chicken is cooked with onion, bell pepper, and tomato.<br>-add cheese sauce for $0.75<br>Substitute grilled chicken or steak for $1.00</p>
      <div class="menu-item">
         <div class="menu-item-name">
           Burrito El Sombrero
         </div>
         <div class="menu-item-price">
            $5.50
         </div>
         <div class="menu-item-description">
           A large flour tortilla stuffed wit ground beef or shredded chicken. Topped with red sauce, lettuce, sour cream, shredded cheese, and tomato. Served with mexican and refried beans. 
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chimichanga
         </div>
         <div class="menu-item-price">
            $6.50
         </div>
         <div class="menu-item-description">
            A flour tortilla stuffed with shredded chicken or chunks of beef, then deep fried and topped with cheese sauce. Served with mexican rice, refried beans, lettuce, sour cream, guacamole, and pico de gallo.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Fajitas
         </div>
         <div class="menu-item-price">
            $6.50
         </div>
         <div class="menu-item-description">
            Tender strips of steak or chicken with sauteed onion, bell pepper, and tomato. Served with mexican rice, refried beans, lettuce, sour cream, guacamole, and pico de gallo.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Taco Salad
         </div>
         <div class="menu-item-price">
            $5.50
         </div>
         <div class="menu-item-description">
            A crispy flour tortilla with cheese sauce, topped with ground beef or shredded chicken, lettuce, sour cream, tomato, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Taco Salad Fajita
         </div>
         <div class="menu-item-price">
            $6.25
         </div>
         <div class="menu-item-description">
            A crispy flour tortilla with cheese sauce, topped with your choice of steak or chicken with sauteed, onion, bell pepper, and tomato. Covered with lettuce, sour cream, tomato, and shredded cheese.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Taquitos Mexicanos
         </div>
         <div class="menu-item-price">
            $5.25
         </div>
         <div class="menu-item-description">
            Two rolled corn tortillas stuffed with shredded chicken or chunks of beef. Deep fried served with mexican rice, refried beans, lettuce, sour cream, guacamole, and pico de gallo.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Huevos con Chorizo
         </div>
         <div class="menu-item-price">
            $5.25
         </div>
         <div class="menu-item-description">
            Scrambled eggs with mexican sausage. Served with mexican rice and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Huevos Rancheros
         </div>
         <div class="menu-item-price">
            $5.25
         </div>
         <div class="menu-item-description">
            Ranch style eggs topped with hot ranchero sauce. Served with mexican rice and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Special Lunch #1
         </div>
         <div class="menu-item-price">
            $5.75
         </div>
         <div class="menu-item-description">
            Chile relleno, taco, refried beans, and guacamole salad.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Special Lunch #2
         </div>
         <div class="menu-item-price">
            $5.25
         </div>
         <div class="menu-item-description">
           One burrito topped with red sauce. Served mexican rice and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Special Lunch #3
         </div>
         <div class="menu-item-price">
            $5.25
         </div>
         <div class="menu-item-description">
            One bean burrito, one cheese enchilada topped with red sauce. Served with mexican rice.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Speedy Gonzales
         </div>
         <div class="menu-item-price">
            $4.25
         </div>
         <div class="menu-item-description">
            One taco, one enchilada covered with enchilada sauce. Your choice of mexican rice or refried beans.
         </div>
      </div>  
<h2 class="menu-section-title">Child's Menu</h2>
     <p><strong>$4.50</strong><br><strong>Drink Included</strong><br>-Over 10 year old add $1.50<br>-add cheese sauce for $0.75<br>Substitute grilled chicken or steak add $1.00</p>
      <div class="menu-item">
         <div class="menu-item-name">
           Taco Plate
         </div>
         <div class="menu-item-price">
            
         </div>
         <div class="menu-item-description">
           One taco, mexican rice and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Mini Nachos
         </div>
         <div class="menu-item-price">
            
         </div>
         <div class="menu-item-description">
            Crispy tortilla chips with cheese sauce add ground beef.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Pancho's
         </div>
         <div class="menu-item-price">
            
         </div>
         <div class="menu-item-description">
            A small hamburger/cheeseburger with fries.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chicken Nuggets
         </div>
         <div class="menu-item-price">
           
         </div>
         <div class="menu-item-description">
            5 Chicken nuggets with fries.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Burrito Plate
         </div>
         <div class="menu-item-price">
            
         </div>
         <div class="menu-item-description">
            Burrito with mexican rice and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Enchilada Plate
         </div>
         <div class="menu-item-price">
            
         </div>
         <div class="menu-item-description">
            One enchilada, mexican rice and refried beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Quesadilla Plate 
         </div>
         <div class="menu-item-price">
            
         </div>
         <div class="menu-item-description">
            Cheese quesadilla, mexican rice and beans.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Taco Salad
         </div>
         <div class="menu-item-price">
            
         </div>
         <div class="menu-item-description">
            
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
            Chicken Tender  

         </div>
         <div class="menu-item-price">
            
         </div>
         <div class="menu-item-description">
            Two chicken tender strips with fries.
         </div>
      </div>
      <div class="menu-item">
         <div class="menu-item-name">
           Cheese Sticks (4) with fries
         </div>
         <div class="menu-item-price">
            
         </div>
         <div class="menu-item-description">
           
         </div>
      </div>
<h2 class="menu-section-title">Vegetarian Menu</h2>
     <p><strong>$6.99</strong><br>A.One chalupa, one cheese enchilada and mexican rice.<br>B.Two bean bur<!--Dev Project By Luis Ortiz-->ritos topped with cheese sauce.<br>C.One bean burrito, one cheese enchilada and a bean tostada.<br>D.One bean burrito, one chalupa and a cheese quesadilla.<br>E.One chile relleno, one bean tostada and mexican rice.</p>
      
    <!--<div class="jumbotron">
      <div class="container">
        <h2>Call Us Today</h2>
        <p>Order Your Favorite Mexican Food.</p>
        <a class="btn" href="#">CALL NOW</path>
</svg></a>
      </div>
    </div>-->

    <div class="footer">
      <div class="container">
        <p>&copy;Dev Project by Luis Ortiz</p>
      </div>
    </div>
  <style>
/* If the screen size is 601px wide or more, set the font-size of <div> to 80px */
@media screen and (min-width: 601px) {
  div.example {
    font-size: 80px;
  }
}

/* If the screen size is 600px wide or less, set the font-size of <div> to 30px */
@media screen and (max-width: 600px) {
  div.example {
    font-size: 30px;
  }
}        
    html, body {
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
}
h1 {
  color: black;
}

.container {
  margin: 0 auto;
  max-width: 940px; 
  padding: 0 10px;
  color: #00000;
}

.header {
  background: url(http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg) no-repeat center center; 
  background-size: cover;
  height: 800px;
  text-align: center; 
  text-color: black;
}
.logo {
  height: 80px;
  width: 80px;
  background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  background-size: contain;
  background-repeat: no-repeat;
  display: inline-block;
  position: relative;
  top: 1em;
}

.header .container {
  position: relative;
  top: 200px;
}

.header h1 {
  color: black;
  line-height: 100px; 
  font-size: 80px;
  margin-top: 0;
  margin-bottom: 80px;
  text-transform: uppercase; 
}

@media (min-width:850px) {
  .header h1 {
    font-size: 120px;
  }
}

.header p {
  color: black;
  font-weight: 500;
  letter-spacing: 8px;
  margin-bottom: 40px;
  margin-top: 0;
  text-transform: uppercase; 
  font-size: 50px;
}

.btn {
  color: #fff;
  background: #000;
  padding: 10px 40px;
  text-decoration: none; 
  transition: background .5s; 
}

    .nav { 
  background: #000;
  height: 10px; 
  width: 100%;
}

.nav ul {
  height: 80px;
  list-style: none;
  margin: 0 auto; 
  padding: 0;
}

.nav ul li {
  color: #fff;
  display: inline-block; 
  height: 80px;
  line-height: 80px; 
  list-style: none;
  padding: 0 19px;
  transition: background .5s; 
}

.btn:hover, .nav ul li:hover {
  background: #117bff;
  cursor: pointer; 
  transition: background .5s;  
}
    
    
    

.main .container {
  margin: 80px auto;
}

.main img {
  float: left;
  margin: 50px 80px 50px 0;
}

.jumbotron {
  background: url(http://www.lacasadesamuel.com/imgs/desconocidojeje.jpg) center center;
  background-size: cover;
  height: 600px; 
}

.jumbotron .container {
  position: relative;
  top: 220px;
}

.jumbotron h2 {
  color: black;
  text-align: right; 
  font-size: 45px;
}

.jumbotron p {
  color: black; 
  text-align: right; 
  font-size: 25px;
}

.jumbotron .btn {
  margin: 10px 0 0;
  float: right; 
  font-size: 20px;
}

.footer { 
  background: #000;
  height: 80px;
}

.footer p { 
  color: #fff;
  font-size: 14px;  
  height: 80px; 
  line-height: 80px;
  margin: 0;  
}

@media (max-width: 500px) {
  .header h1 {
    font-size: 50px;
    line-height: 64px;
  }

  .main, .jumbotron {
    padding: 0 30px;
  }

  .main img {
    width: 100%;
  }
 @media only screen and (max-width: 1500px) {
  .page-title {
    width: 800px;
  }
}

@media only screen and (min-width: 320px) and (max-width: 1500px) {
  .gallery-item .thumbnail {
    width: 95%;
  }
}

@media only screen and (min-resolution: 150dpi) {
  .logo {
    background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  }
}

@media only screen and (max-resolution: 150dpi) and (max-width: 1500px) {
  .page-description {
    font-size: 20px;
  }
}
  @media only screen and (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
    /* CSS ruleset */
}
  @media only screen and (min-resolution: 150dpi)
    .nav
    .container
  </style>
  </div>
  
      <!-- Special Days -->
<!--Dev Project By Luis Ortiz-->
  <div id="speciald" class="tabcontent">
  <div class="header">
      <div class="container">
        <h1>"El Sombrero"</h1>
        <p>Special Days</p>
      </div>
    </div>

    <div class="nav">
      <div class="container">
        <!--<ul>
    <li><strong>Home</strong></li>
    <li><a href="about.html">About Us</a></li>
    <li><a href="menu.html">Menu</a></li>
    <li><a href="specialties.html">Specialties "El Sombrero</a></li>
    <li><a href="special.html">Special Menus</a></li>
    <li><a href="find.html">Find Us</a></li>
        </ul>-->
      </div>
    </div>
    <div class="main">
      <div class="container">
        <!--<img src="https://lh5.googleusercontent.com/-NuP51-nUCBc/WcBApoe6gNI/AAAAAAAAAVA/OrxNweTPZcsW1gPNi7Iu22QFUWEsLkTHACLIBGAYYCw/w284-h160-k-no/" height="128" width="196">-->
      <h2>Special Days</h2>
    <p>-Valentine's Day: 20% OFF Everything<br>-Mother's Day: 15% OFF Everything<br>-5 De Mayo: 15% OFF Everything<br>-Super Bowl Day: 15% OFF Everything & Buy One Beer and Get The Second One For Free<br>-Is your birthday? We have a something special for you.</p>
        <p><strong>Closed at Christmas, New Year, Labor Day, and 4 Of July.</p>
        <p></p>
        <p></p>
      </div>
    </div>

    <!--<div class="jumbotron">
      <div class="container">
        <h2>Call Us Today</h2>
        <p>Order Your Favorite Mexican Food.</p>
        <a class="btn" href="#">CALL NOW</path>
</svg></a>
      </div>
    </div>-->

    <div class="footer">
      <div class="container">
        <p>&copy;Dev Project by Luis Ortiz</p>
      </div>
    </div>
  <style>
/* If the screen size is 601px wide or more, set the font-size of <div> to 80px */
@media screen and (min-width: 601px) {
  div.example {
    font-size: 80px;
  }
}

/* If the screen size is 600px wide or less, set the font-size of <div> to 30px */
@media screen and (max-width: 600px) {
  div.example {
    font-size: 30px;
  }
}        
    html, body {
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
}
h1 {
  color: black;
}

.container {
  margin: 0 auto;
  max-width: 940px; 
  padding: 0 10px;
  color: #00000;
}

.header {
  background: url(http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg) no-repeat center center; 
  background-size: cover;
  height: 800px;
  text-align: center; 
  text-color: black;
}
.logo {
  height: 80px;
  width: 80px;
  background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  background-size: contain;
  background-repeat: no-repeat;
  display: inline-block;
  position: relative;
  top: 1em;
}

.header .container {
  position: relative;
  top: 200px;
}

.header h1 {
  color: black;
  line-height: 100px; 
  font-size: 80px;
  margin-top: 0;
  margin-bottom: 80px;
  text-transform: uppercase; 
}

@media (min-width:850px) {
  .header h1 {
    font-size: 120px;
  }
}

.header p {
  color: black;
  font-weight: 500;
  letter-spacing: 8px;
  margin-bottom: 40px;
  margin-top: 0;
  text-transform: uppercase; 
  font-size: 50px;
}

.btn {
  color: #fff;
  background: #000;
  padding: 10px 40px;
  text-decoration: none; 
  transition: background .5s; 
}

    .nav { 
  background: #000;
  height: 10px; 
  width: 100%;
}

.nav ul {
  height: 80px;
  list-style: none;
  margin: 0 auto; 
  padding: 0;
}

.nav ul li {
  color: #fff;
  display: inline-block; 
  height: 80px;
  line-height: 80px; 
  list-style: none;
  padding: 0 19px;
  transition: background .5s; 
}

.btn:hover, .nav ul li:hover {
  background: #117bff;
  cursor: pointer; 
  transition: background .5s;  
}
    
    
    

.main .container {
  margin: 80px auto;
}

.main img {
  float: left;
  margin: 50px 80px 50px 0;
}

.jumbotron {
  background: url(http://www.lacasadesamuel.com/imgs/desconocidojeje.jpg) center center;
  background-size: cover;
  height: 600px; 
}

.jumbotron .container {
  position: relative;
  top: 220px;
}

.jumbotron h2 {
  color: black;
  text-align: right; 
  font-size: 45px;
}

.jumbotron p {
  color: black; 
  text-align: right; 
  font-size: 25px;
}

.jumbotron .btn {
  margin: 10px 0 0;
  float: right; 
  font-size: 20px;
}

.footer { 
  background: #000;
  height: 80px;
}

.footer p { 
  color: #fff;
  font-size: 14px;  
  height: 80px; 
  line-height: 80px;
  margin: 0;  
}

@media (max-width: 500px) {
  .header h1 {
    font-size: 50px;
    line-height: 64px;
  }

  .main, .jumbotron {
    padding: 0 30px;
  }

  .main img {
    width: 100%;
  }
 @media only screen and (max-width: 1500px) {
  .page-title {
    width: 800px;
  }
}

@media only screen and (min-width: 320px) and (max-width: 1500px) {
  .gallery-item .thumbnail {
    width: 95%;
  }
}

@media only screen and (min-resolution: 150dpi) {
  .logo {
    background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  }
}

@media only screen and (max-resolution: 150dpi) and (max-width: 1500px) {
  .page-description {
    font-size: 20px;
  }
}
  @media only screen and (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
    /* CSS ruleset */
}
  @media only screen and (min-resolution: 150dpi)
    .nav
    .container
  </style>
  </div>

      <!-- Find Us -->
<!--Dev Project By Luis Ortiz-->
<div id="find" class="tabcontent">
  <div class="header">
      <div class="container">
        <h1>"El Sombrero"</h1>
        <p>Find Us</p>
      </div>
    </div>

    <div class="nav">
      <div class="container">
        <!--<ul>
    <li><strong>Home</strong></li>
    <li><a href="about.html">About Us</a></li>
    <li><a href="menu.html">Menu</a></li>
    <li><a href="specialties.html">Specialties "El Sombrero</a></li>
    <li><a href="special.html">Special Menus</a></li>
    <li><a href="find.html">Find Us</a></li>
        </ul>-->
      </div>
    </div>
    <div class="main">
      <div class="container">
        <!--<img src="https://lh5.googleusercontent.com/-NuP51-nUCBc/WcBApoe6gNI/AAAAAAAAAVA/OrxNweTPZcsW1gPNi7Iu22QFUWEsLkTHACLIBGAYYCw/w284-h160-k-no/" height="128" width="196">--><!--Dev Project By Luis Ortiz-->
        <h2>"El Sombrero" Mexican Restaurant</h2>
        <p>731-783-0079</p>
        <p>29 A GARRETT DRIVE<br>MEDINA, TN 38358</p>
        <p><strong>Business Hours:</strong><br>Sunday: 11:00AM-9:00PM<br>Monday: 11:00AM-10:30PM<br>Tuesday: 11:00AM-10:30PM<br>Wednesday: 11:00AM-10:30PM<br>Thursday: 11:00AM-10:30PM<br>Friday: 11:00AM-11:00PM<br>Saturday: 11:00AM-11:00PM</p>
      </div>
    </div>

    <!--<div class="jumbotron">
      <div class="container">
        <h2>Call Us Today</h2>
        <p>Order Your Favorite Mexican Food.</p>
        <a class="btn" href="#">CALL NOW</path>
</svg></a>
      </div>
    </div>-->

    <div class="footer">
      <div class="container">
        <p>&copy;Dev Project by Luis Ortiz</p>
      </div>
    </div>
  <style>
/* If the screen size is 601px wide or more, set the font-size of <div> to 80px */
@media screen and (min-width: 601px) {
  div.example {
    font-size: 80px;
  }
}

/* If the screen size is 600px wide or less, set the font-size of <div> to 30px */
@media screen and (max-width: 600px) {
  div.example {
    font-size: 30px;
  }
}        
    html, body {
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
}
h1 {
  color: black;
  text-align: center;
}
    h2 {
      text-align: center;
    }
    p {
      text-align: center;
    }
.container {
  margin: 0 auto;
  max-width: 940px; 
  padding: 0 10px;
  color: #00000;
}

.header {
  background: url(http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg) no-repeat center center; 
  background-size: cover;
  height: 700px;
  text-align: center; 
  text-color: black;
}
.logo {
  height: 80px;
  width: 80px;
  background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  background-size: contain;
  background-repeat: no-repeat;
  display: inline-block;
  position: relative;
  top: 1em;
}

.header .container {
  position: relative;
  top: 200px;
}

.header h1 {
  color: black;
  line-height: 100px; 
  font-size: 80px;
  margin-top: 0;
  margin-bottom: 80px;
  text-transform: uppercase; 
}

@media (min-width:850px) {
  .header h1 {
    font-size: 120px;
  }
}

.header p {
  color: black;
  font-weight: 500;
  letter-spacing: 8px;
  margin-bottom: 40px;
  margin-top: 0;
  text-transform: uppercase; 
  font-size: 50px;
}

.btn {
  color: #fff;
  background: #000;
  padding: 10px 40px;
  text-decoration: none; 
  transition: background .5s; 
}

    .nav { 
  background: #000;
  height: 10px; 
  width: 100%;
}

.nav ul {
  height: 80px;
  list-style: none;
  margin: 0 auto; 
  padding: 0;
}

.nav ul li {
  color: #fff;
  display: inline-block; 
  height: 80px;
  line-height: 80px; 
  list-style: none;
  padding: 0 19px;
  transition: background .5s; 
}

.btn:hover, .nav ul li:hover {
  background: #117bff;
  cursor: pointer; 
  transition: background .5s;  
}
    
    
    

.main .container {
  margin: 80px auto;
}

.main img {
  float: left;
  margin: 50px 80px 50px 0;
}

.jumbotron {
  background: url(http://www.lacasadesamuel.com/imgs/desconocidojeje.jpg) center center;
  background-size: cover;
  height: 600px; 
}

.jumbotron .container {
  position: relative;
  top: 220px;
}

.jumbotron h2 {
  color: black;
  text-align: right; 
  font-size: 45px;
}

.jumbotron p {
  color: black; 
  text-align: right; 
  font-size: 25px;
}

.jumbotron .btn {
  margin: 10px 0 0;
  float: right; 
  font-size: 20px;
}

.footer { 
  background: #000;
  height: 80px;
}

.footer p { 
  color: #fff;
  font-size: 14px;  
  height: 80px; 
  line-height: 80px;
  margin: 0;  
}

@media (max-width: 500px) {
  .header h1 {
    font-size: 50px;
    line-height: 64px;
  }

  .main, .jumbotron {
    padding: 0 30px;
  }

  .main img {
    width: 100%;
  }
 @media only screen and (max-width: 1500px) {
  .page-title {
    width: 800px;
  }
}

@media only screen and (min-width: 320px) and (max-width: 1500px) {
  .gallery-item .thumbnail {
    width: 95%;
  }
}

@media only screen and (min-resolution: 150dpi) {
  .logo {
    background-image: url("http://www.habanerosgrillbar.com/images/tortilla_soup_mexican.jpg");
  }
}

@media only screen and (max-resolution: 150dpi) and (max-width: 1500px) {
  .page-description {
    font-size: 20px;
  }
}
  @media only screen and (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
    /* CSS ruleset */
}
  @media only screen and (min-resolution: 150dpi)
    .nav
    .container
  </style>
  </div>
  
  
  <style>
  * {box-sizing: border-box}

/* Set height of body and the document to 100% */
body, html {
    height: 100%;
    margin: 0;
    font-family: Arial;
    padding: 0px 10px;
}

/* Style tab links */
.tablink {
    background-color: #FFA000;
    color: white;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 12px 16px;
    font-size: 13px;
    width: 16.666%;
    height: 11%;
}
.tablink.small {
    background-color: #FFA000;
    color: white;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 12px 16px;
    font-size: 13px;
    width: 16.666%;
    height: 3%;
}
.tablink:hover {
    background-color: #FFCA28;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
    color: black;
    display: none;
    padding: 0px 0px;
    height: 90%;
    width: 100%;
}

#Home {background-color: white;}
#Menu {background-color: white;}
#Contact {background-color: white;}
#About {background-color: white;}
#Contact {background-color: white;}
#About {background-color: white;}

</style>
<script>
function openPage(pageName,elmnt,color) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablink");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].style.backgroundColor = "";
    }
    document.getElementById(pageName).style.display = "block";
    elmnt.style.backgroundColor = color;

}
// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
