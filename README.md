<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title> ESCRIME </title>
    <!-- === CSS === --> 
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" id="colorCssFile" href="style.css">
    <link rel="icon" href="image_site.png">
</head>

<body>
    <!-- === Barre De Navigation === -->
    <nav class="navbar">
        <ul class="barre_nav">
            <li class="active"> <a href ="index.html"> Accueil </a> </li>
            <li> <a href ="Histoire.html"> Inscription </a> </li>
            <li> <a href ="Explore.html"> Sport </a> </li>
            <li> <a href ="Avis.html"> Renseignement </a> </li>
            <li>
                <input type="checkbox" id="darkmode-toggle">
                <label for="darkmode-toggle"></label>
            </li>
        </ul>
        <img src="barre.png" alt="" class="menu-btn">
    </nav>
    <header>
        <div class="header-content">
            <h2> Bienvenue à la coupe de France des IUT 2024  </h2>
            <div class="line"></div>
            <h3> Organisée par l'IUT de Saint-Denis </h3>
            <img src="./Image/CoupeMonde-.webp" />
        </div>
    </header>
    <script> 
        const menuBtn= document.querySelector('.menu-btn')
        const navlinks= document.querySelector('.barre_nav')

        menuBtn.addEventListener('click',()=>{
            navlinks.classList.toggle('mobile-menu')
        })
        </script>
    <script src="switch.js"></script>
</body>
