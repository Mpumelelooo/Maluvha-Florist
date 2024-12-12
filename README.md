<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maluvha Florist</title>
</head>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">

<link rel="icon" type="image/x-icon" href="maluvhapictures/maluvhalogo2idea-Photoroom.png">

<style>
body{
  margin: 0;
  padding: 0;
  background-color: pink;
  background-image: url(maluvhapictures/maluvhapinkfront.jpeg);
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
  font-family: Montserrat;

}

.Logo img{
  width: 80%;
  max-width: 300px;
  margin: 20px auto;
  display: block;


}
h1{
  margin: 0;
  padding: 0;
}

h1{
text-align: center;
color: brown;
font-size: 1.5 rem;
line-height: 1.2;
}

.shop-btn{
  display: block;
  margin: 20px auto;
  background-color: rgb(210, 128, 142);
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 5px;
  font-family: 'Montserrat';
  cursor: pointer;
  text-align: center;
  width: 200px;
}

.shop-btn:hover{
  background-color: brown;
}

@media (max-width: 768px) {
  body {
    background-size: cover;
  }
}

h1 {
  font-size: 1.5rem;
  padding: 0 10px;
}

.shop-btn {
  width: 150px;
  font-size: 0.9rem;
}

.Logo img{
  width: 80%
}

.footer-board{
  background-color: rgb(210, 128, 142);
  text-align: center;
  color: white;
  padding: 20px 0;
}

@media (max-width: 480px) {
  h1 {
    font-size: 1.2rem;
    line-height: 1.2;
  }

  .shop-btn {
    width: 140px;
    font-size: 0.8rem;
  }
}


  
</style>
<body>

  <div class="Logo">
    <img src="maluvhapictures/maluvhalogo2idea-Photoroom.png">
  </div>

  <div class="tagline">
    <h1>WELCOME TO <br>
      MALUVHA FLORIST</h1>
  </div><br><br><br><br><br><br>

  <button onclick="location.href='shopnow.html'" class="shop-btn"> SHOP NOW</button>
  <br><br><br><br><br><br><br><br><br><br><br><br>

  <div class="footer-board">
    <footer class="footer">
      COPYRIGHTS &copy; 2024. All Rights Reserved. Designed by Mpumelelo Hlongwane
    </footer>
   </div>
  
  <script src="js/script.js"></script>
  
</body>
</html>
