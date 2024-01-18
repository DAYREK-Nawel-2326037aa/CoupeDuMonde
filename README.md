
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title> Coupe du Monde </title>
    <link rel="icon" href="image_site.png">
    <!-- === CSS === --> 
    <link rel="stylesheet" href="./styles.css">
    <link rel="stylesheet" id="colorCssFile" href="./styles.css">
    <link rel="icon" href="image_site.png">
</head>
<body>
    <!-- === Barre De Navigation === -->
    <nav class="navbar">
        <ul class="barre_nav">
            <li class="active"> <a href ="Coupe.html"> Accueil </a> </li>
            <li> <a href ="Histoire.html"> Inscription </a> </li>
            <li> <a href ="Explore.html"> Sport </a> </li>
            <li> <a href ="Avis.html"> Renseignement </a> </li>
            <li>
                <input type="checkbox" id="darkmode-toggle">
                <label for="darkmode-toggle"></label>
            </li>
        </ul>
        <img src="./barre.png" alt="" class="menu-btn">
    </nav>
    <section class="histoire"> 
    <div class="title">
        <h1> Les sports </h1>
    </div>
<div class="row">
    <h2> Football </h2>
    <img src="./Football.webp" alt="Football" class="photo" width="340" height="280">
		<a href="RegleFootball.html" class="ctn"> Voir les règles</a>
    </div>
    <div class="row">
        <h2> Handball </h2>
        <img src="./Football.webp" alt="Football" class="photo" width="340" height="280">
            <a href="RegleFootball.html" class="ctn"> Voir les règles</a>
        </div>
        <div class="row">
            <h2> Touch Rugby</h2>
            <img src="./Football.webp" alt="Football" class="photo" width="340" height="280">
                <a href="RegleFootball.html" class="ctn"> Voir les règles</a>
                <h2> Tennis </h2>
                <img src="./Football.webp" alt="Football" class="photo" width="340" height="280">
                    <a href="RegleFootball.html" class="ctn"> Voir les règles</a>
                    <h2> Volley </h2>
                    <img src="./Football.webp" alt="Football" class="photo" width="340" height="280">
                        <a href="RegleFootball.html" class="ctn"> Voir les règles</a>
                    </div>
                    <div class="2">
                        <h2> Tenis de table</h2>
                        <img src="./Football.webp" alt="Football" class="photo" width="340" height="280">
                            <a href="RegleFootball.html" class="ctn"> Voir les règles</a>
                            <h2> Basketball </h2>
                            <img src="./Football.webp" alt="Football" class="photo" width="340" height="280">
                                <a href="RegleFootball.html" class="ctn"> Voir les règles</a>
                            </div>
</section>


















<script> 
    const menuBtn= document.querySelector('.menu-btn')
    const navlinks= document.querySelector('.barre_nav')
    
    menuBtn.addEventListener('click',()=>{
        navlinks.classList.toggle('mobile-menu')
    })
    </script>
	<script src="switch.js"></script>
</body>
</html>
