<!DOCTYPE html>
<html>
    <head>
        <title>Just Haikyuu</title>
        <link rel="icon" href="logo.ico" type="image/x-icon" >
        <script src="https://www.w3schools.com/lib/w3.js"></script>
        <link rel="stylesheet" href="stylesheet.css">
        <style>
        .button
         {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
        }
        </style>
          
    </head>

<body BACKGROUND = 'background.jpg'>
<center>
<h1>Welcome to Haikyuu World</h1>

    <img class="haikyuu" src="slideshow1.jpg" width="100%">
    <img class="haikyuu" src="slideshow2.jpg" width="100%">
    <img class="haikyuu" src="slideshow3.jpg" width="100%">
    <img class="haikyuu" src="slideshow4.jpg" width="100%">
    <img class="haikyuu" src="slideshow4.jpg" width="100%">

<script>
w3.slideshow(".haikyuu", 1000);
</script>

<br/>
<h2>The Characters</h2>

<p><button onclick="w3.addClass('.city','marked')" class="button">More Design</button></p>

<p>
    <strong> Hinata Shoyo </strong><button onclick="w3.toggleShow('#hinata')" class="button" >Hide</button>
</p>


<div id="hinata" class="city" class="img">

    <img src="img_hinata.jpg" alt="hinata" style="width:200px; height:200px;">
    <p>
        The main protagonist. Hinata was a first-year student at Karasuno High and one of the volleyball team's middle blocker.
    </p>

</div>


<p>
    <strong> Tobio Kageyama </strong><button onclick="w3.toggleShow('#kageyama')" class="button" >Hide</button>
</p>


<div id="kageyama" class="city">

    <img src="img_kageyama.jpg" alt="kageyama" style="width:200px; height:200px;">
    <p>
        The deuteragonist. Kageyama was a first-year student at Karasuno High and plays as the starting setter for the boys' volleyball club.
    </p>

</div>


<p>
    <strong> Kei Tsukishima </strong><button onclick="w3.toggleShow('#tsuki')" class="button" >Hide</button>
</p>


<div id="tsuki" class="city">

    <img src="img_tsuki.jpg" alt="tsuki" style="width:200px; height:200px;">
    <p>
        A first year at Karasuno High. He plays as one of the starting middle blockers on the boys volleyball team.
    </p>

</div>


<p>
    <strong> Tadashi Yamaguchi </strong><button onclick="w3.toggleShow('#yamaguchi')" class="button" >Hide</button>
</p>

<div id="yamaguchi" class="city">

    <img src="img_yamaguchi.jpg" alt="yamaguchi" style="width:200px; height:200px;">
    <p>
        A first year student at Karasuno High. He plays on the boys volleyball team as a middle blocker and pinch server.
    </p>

</div>


<br><br><br><br><br>

<h3>
    <strong> Youtube Link </strong><button onclick="w3.toggleShow('#link')" class="button" > Hide</button>
</h3>

<div id="link" class="city">

    <p>
        <a href="https://www.youtube.com/watch?v=LL-XvudvRDA"> Haikyuu Above OST </a>
    </p>

</div>

</center>

<br><br><br><br><br>

<p>
    <button onclick="w3.toggleShow('#Pic')" style="float: left;" class="button" >Click Me</button>
</p>

<br><br>
<div id="Pic" class="city" id="pic">     
    <h4>Click The Pic</h4>

    <a href="https://www.facebook.com/bellagarrote">
        <img src="me.jpg" alt="me" style="width:350px;height:600px;">
    </a>

</div>

<br><br><br><br><br>


</body>
</html>
