<!DOCTYPE html>
<html>

<head>
  <link rel="stylesheet" href="test.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0" />
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title></title>
</head>

<body>
  <div class="background">
    <img src="bg.jpeg">
      <p class="bg-description1">Aseda<span>'</span>s </p>
       <p class="bg-description2">Restaurant</p>
       <p class="bg-description3">welcome</p>
       <p class="bg-description4">to</p>
  </div>
 <nav>
   <div class="nav-bar">
     <a href="#">Home</a>
      <a href="#">Dishes</a>
       <a href="#">Order</a>
        <a href="#">Info</a>
   </div>
 </nav>
<main>
<div class="forewords">
 We ensure that our customers get to eat food that taste as how they want it.
</div>
<div class="our-service">
  <div class="s1">Our services</div>
  <div class="s2">Home delivery</div>
  <div class="s3">Training services</div>
  <div class="s4">Assisted service</div>
  <div class="s5">buffey</div>
</div>

<div class="dish">
  <input type="radio" name="accordion" id="accordion1">
  <label for="accordion1" class="kind-of-food"> food menu</label>
  
 
    
    <div class="dish1">
    <input type="radio" name="accordion" id="accord1">
    <label for="accord1">local</label>
    <div class="accordion-content">
      <div><a href="#banku">banku</a></div>
       <div><a href="#ampesi">ampesi</a></div>
         <div><a href="#fufu">fufu</a></div>
          <div><a href="#gobe">beans</a></div>
    </div>
    </div>
    
    <div class="dish1">
    <input type="radio" name="accordion" id="accord2">
    <label for="accord2">continental</label>
    <div  class="accordion-content">
      <div><a href="#">jollof</a></div>
       <div><a href="#">chow mein</a></div>
        <div><a href="#">dumplings</a></div>
         <div><a href="#"> fried rice</a></div>
          <div><a href="#">roast lamb salad</a></div>
    </div>
    </div>
    
    <div class="dish1">
    <input type="radio" name="accordion" id="accord3">
    <label for="accord3">fast food</label>
    <div  class="accordion-content">
      <div><a href="#">noodles</a></div>
      <div><a href="#">burger</a></div>
      <div><a href="#">french fries</a></div>
      <div><a href="#">pizza</a></div>
     </div>
     </div>
     
     <div class="dish1">
    <input type="radio" name="accordion" id="accord4">
    <label for="accord4">beverage</label>
    <div class="accordion-content">
      <div><a href="#">coffee</a></div>
      <div><a href="#">wine</a></div>
     <!-- <p>banku</p>
      <p>fufu</p>
      <p>beans</p>-->
    </div>
    </div>
  </div>
</div>

<!--<div class="dropdown">
  <div>Kind of dish</div>
  <div class="dropdown-description">
  <a href="#local">Local</a>
  <a href="#">continental</a>
  <a href="#">fast food</a>
</div>
</div>-->



   <div id="banku" class="menu-lightbox">
    <span class="close"><a href="#">X</a></span>
     <div class="menu-gallery">
     <img src="banku.jpeg" alt="">
     <span class="local-price">Gh¢45.00</span>
     <span>banku</span>
   </div>
   </div> 
   
   
   <div id="ampesi"class="menu-lightbox">
       <span class="close"><a href="#">X</a></span>
       <div class="menu-gallery">
     <img src="ampesi.jpeg" alt="">
     <span class="local-price">Gh¢30.00</span>
     <span>ampesi</span>
     </div>
   </div>
   
     <div  id="fufu" class="menu-lightbox">
         <span class="close">"<a href="#">X</a></span>
          <div class="menu-gallery">
       <img src="fufu.jpeg" alt="">
       <span class="local-price">Gh¢65.00</span>
       <span>fufu</span>
     </div>
   </div>
   
 
   <div  id="gobe" class="menu-lightbox">
       <span class="close"><a href="#">X</span>
        <div class="menu-gallery">
     <img src="gobe.jpeg" alt="">
     <span class="local-price">Gh¢25.00</span>
     <span>beans</span>
   </div>
 </div>
  
   
   
   <p class="order">order form</p>
<div class="order-form">

  <form action="#" method="get">
     <p>personal details</p>
     
  <div class="order-input">
    <i class="material-symbols-outlined">person</i>
     <input type="text">
  </div>
  
  <div class="order-input">
    <i >telephone</i>
    <input type="tel">
  </div>
  
    <div class="order-input">
      <i>email</i>
      <input type="email">
    </div>
  
  <div class="order-input">
<i class="fa fa-map-marker"></i>
<input type="text">
</div>
<p class="order-details">order-details</p>
<div class="order-input">
  <i>dish</i>
  <input type="text">
  </div>
  
  <div class="order-input">
  <i>amount</i>
  <input type="text">
  </div>
 <div class="order-input"class="locate">
  <i>Location</i>
  <input type="text">
  </div>
  <div class="order-input"class="locate">
  <input type="submit">
  </div>
  
  </form>
</div>

<table>
  <thead>
    <tr>
      <th>Working days</th>
      <th>Time</th>
    </tr>
    <tr>
    </tr>
    <tbody>
      <tr>
        <td>Monday</td>
        <td>8:00am-11pm</td>
      </tr>
      <tr>
        <td>Tuesday</td>
         <td>8:00am-11pm</td>
      </tr>
      <tr>
         <tr>
        <td>Wednesday</td>
         <td>8:00am-11pm</td>
         </tr>
          <tr>
        <td>Thursday</td>
         <td>8:00am-11pm</td>
         </tr>
          <tr>
        <td>Friday</td>
         <td>8:00am-11pm</td>
         </tr>
          <tr>
        <td>Saturday</td>
         <td>8:00am-10pm</td>
         </tr>
      </tr>
    </tbody>
  </thead>
</table>

</main>
<footer>
  <div class="footer">
    <div>Aseda's Restaurant</div>
    <div>
      <div><a href="#">Location:Amasaman,Obeyeyie</a></div>
     <div><a href="#">contact:0559362851</a></div>
       <div><a href="#">about</a></div>
      
    </div>
  </div>
  <div class="copyright">©copyright</div>
</footer>
 
</body>

</html 









