# a
<html lang="en">
<head>
    <meta charset="UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Healza</title>
    <link rel="stylesheet" href="style.css">
    <style>
        
        h1{
            color: powderblue;
            font: bold;
        }
        .hero{
            background-color:antiquewhite;
            background-image: url(<"https://lh3.googleusercontent.com/qHtzMXqojw7j3FH8_kfoQZf4a7q_KMWtI5XCRWhNlhhVcS7fSXAKErGHvvOxoKmYcxcowlTrZ4DJf9rAqe_Kw3u_H3WlbC4-RfHyoFabEkZwJm9nKbMWqwi6lPTPhYqlLBGjJofMRw=w2400?source=screenshot.guru"> <img src="https://lh3.googleusercontent.com/qHtzMXqojw7j3FH8_kfoQZf4a7q_KMWtI5XCRWhNlhhVcS7fSXAKErGHvvOxoKmYcxcowlTrZ4DJf9rAqe_Kw3u_H3WlbC4-RfHyoFabEkZwJm9nKbMWqwi6lPTPhYqlLBGjJofMRw=w600-h315-p-k");
            background-repeat: no-repeat;
            background-size: 100%;
           
            width:30 px;
        border: 15 px solid green;
        padding:50 px;
        margin:20 px;

        }
       nav{
           display:flex;
           align-items:center;
           justify-content:space-between;
       }
       .logo{
           width:30px;
           height:20px;
       }
       nav ul li{
           display:inline-block;
            list-style:none;
            margin: 10px  30px;

       }
        
    </style>
</head>
<body style="text-align: center">
    <div class="hero">
       <nav> <img src="https://lh3.googleusercontent.com/zvG7DM-7Wsi4Ys-NoZgl3R6oj_sTcoaB8pJdBoZ2w90qUaHxZ5V32Y3JgcwhOHTKtRDxxCa3gb29NC1pCDsc10eiMFyjZS19EJlu62qE4rjzGo8rX_OKgDrb-dlRvZ6zD9jQ6XpHhQ=w2400"> 
       <ul>
           <li><a href ="">Home</a></li>
           <li><a href="">About</a></li>
           <li><a href="">Contact</a></li>
           </ul>
        <h2>The one who has health ,has hope and who has hope has everything </h2>
        <style type="text/css">
            input{
                width: 150px;
                display : inline-block;
                margin: 4px;
                
            }
        </style>
    </body>
       <body style="text-align:left">
       <div class="hero">
           
<p>Hii, User</p>
     <form action="" name="myform" >
       <input id="text1" placeholder="Enter your Name">
        
        <br>
        <input id="text2" placeholder="Enter your age">
      
        <br>
        <input id="text3" placeholder="Enter your gender">
        
        <br>
        <input id="number1" placeholder="Enter your height">
       
        <br>
        <input id="number2" placeholder="Enter your weight">
        
        <br>

        
        <h3> Fill in the daily intake</h3>
        <input type="radio" name="intake"value="carbohydrates"> Carbohydrates
        <input type="radio" name="intake"value="proteins"> proteins
        <input type="radio" name="intake"value="vitamins"> vitamins
        

        <h3>How often do you exercise?</h3>
        <input type="radio" name="exercise?"value="Everyday"> Everyday
        <input type="radio" name="exercise?"value="Once or twice a week"> Once or twice a week
        <input type="radio" name="exercise?"value="Once or twice a month"> Once or twice a month
        <input type="radio" name="exercise?"value="Never">Never
        
<h3>What changes do you want in yourself?</h3>
<div>
    <input type="checkbox" id="Increase height" name="Increase height"
           checked>
    <label for="Increase height">Increase height</label>
  </div>
  
  <div>
    <input type="checkbox" id="Increase weight" name="Increase weight">
    <label for="Increase weight">Increase weight</label>
  </div>
  <div>
      <input type="checkbox" id="Reduce weight" name="Reduce weight">
      <label for="Reduce weight">Reduce weight</label>
    </div>
    <div>
      <input type="checkbox" id="Get more fitter" name="Get more fitter">
      <label for="Get more fitter">Get more fitter</label>
    </div>
<button>GENERATE MY PLAN</button>
</form>

<script>
    var form = document.myform;
    console.dir(form);
    consol.log(form.length);
    function fn1()
    
        var str=document.getElementById("text1").value;
        
    }
</script>


</body>
</html>
