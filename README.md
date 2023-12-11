<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cv</title>
  <style>
    *{
    margin: 0;
    padding: 0;
}
body{
    box-sizing: border-box;
}
.cv{
    display: grid;
    grid-template-columns: repeat (4fr);
    grid-template-rows: auto;
    margin: 10px 25%;
}
.dau{
    background-color: #168DC7;
}
.anh{
    display: flex;
    flex-direction: column;
    text-align: center;
    margin-top: 30px;
    color:#F7FFFF;
    font-size: 14px;
    max-height: 180px ;
    border-bottom: 1px solid  ;

}
img{
    max-width: 150px;
    max-height: 150px;
    margin-left: 22%;
    margin-bottom: 20px;
    border-radius: 20px;
}
.tt{
    display: grid;
    margin: 20px 20px;
    color: white;
}
li{
    margin:5px 40px;
}
h2{
    color: black;
}
.than{
    display: grid;
    grid-column: 2/5;
    grid-row: auto;
    background-color: #EEEDEB;
}
.tt2{
    margin: 10px 20px;
}
h3{
    color: #168DC7;
}
@media ( max-width:800px ) {
        .cv{
            max-width: 520px;
            max-height: 520px;
            margin: 0;
        }
}

@media ( max-width: 500px ) {
    li{
        font-size: 8px;
    }
    h3{
        font-size: 12px;
    }
    h2{
        font-size: 15px;
    }
    h1{
        font-size: 20px;
    }
    img{
        margin-top: -10px;        
        margin-left: 50px ;
        max-width: 80px;
        max-height: 80px;
    }
    .cv{
        margin: 0;
        background-color: #EEEDEB;
    }
    .tt{
        top:10px
    }
}
  </style>
</head>
<body>
  <div class="cv">

    <div class="dau">

      <div class="anh">
        <img src="img/th.jpg" alt="">
        <h1> Nguyen Van Dat </h1>
      </div>
      <div class="tt">
        <div class="me">
          <ul>
            <h2> 	&#169; Introduct  </h2>
            <li>Jsem Vietnamec</li>
            <li>V současné době žiji v České republice</li>
          </ul>
        </div>

        <div class="hobby">
            <h2> &#169; Hooby</h2>
            <li>Hraní</li>
            <li>Číst Knihu</li>
            <li>Vytvořte Web</li>
            <li>Cestování</li>
        </div>

        <div class="education">
            <h2> &#169; Education </h2>
            <li>Jsem studentem školy <br> Vyšší odborná škola, <br> Střední průmyslová škola <br> a Střední odborná škola,Varnsdorf</li>
        </div>
      </div>
    </div>
    <!-- thancvv -->
    <div class="than">
      <div class="tt2">
        <div class="h">
          <h3> &#169; Education</h2>
          <li> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tempora ipsam optio quaerat suscipit corrupti placeat nostrum atque quibusdam, in nisi at iusto unde totam mollitia minus quasi nam voluptas repellat. </li>
        </div>
        <div class="h"> 
          <h3> &#169; Seznam</h2>
          <li>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Omnis incidunt iste pariatur magnam, sed minima aperiam porro, nesciunt asperiores consequuntur tenetur velit sint possimus a ratione libero eos necessitatibus vero! </li>
          <li> Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis nesciunt magnam nulla culpa perferendis. Repellendus incidunt saepe amet officiis ipsum? Eum earum iure beatae ullam vitae voluptates maxime quas nisi? </li>
        </div>
        <div class="h">
          <h3> &#169; Navigace </h2>
          <li> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Itaque facilis quasi praesentium quis velit deserunt! Dicta quibusdam doloremque eos sapiente, facere autem illo numquam excepturi consequuntur delectus dolorem, expedita provident? </li>
          <li>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aspernatur nisi dolorum illum tenetur porro aliquid assumenda perferendis numquam inventore? Cumque perspiciatis fuga voluptate! Ea, quis amet tenetur eveniet consequatur laboriosam?</li>
        </div>
        <div class="h">
          <h3> &#169; Tab </h2>
          <li> Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt quos illum, aperiam modi excepturi consequuntur laboriosam distinctio magni architecto hic temporibus atque, fugiat blanditiis neque natus beatae dolor aliquam rem? </li>
          <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat officia recusandae voluptates sunt? Temporibus in aliquam quasi, nobis repellendus voluptas tempora voluptatibus perferendis culpa ullam! Necessitatibus ducimus debitis nobis natus.</li>
        </div>
        <a href="http://127.0.0.1:5501/Table.html#">Go to Section 1</a>
    </div>
  </div>  
</body>
</html>
