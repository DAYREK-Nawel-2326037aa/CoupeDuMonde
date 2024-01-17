/* Google Font */

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

ul{
    list-style: none;
}
.active{
    color :#1c03fc;
    text-decoration: underline;
    font-weight: bold;
}
body , html {
    overflow-x: hidden;
}
viewport{
    width: device-width;
    height: device-height;

}
/* NAVBAR */
.Image{
    position: absolute;
    top: 0;
    left: 0; 
    display: flex;
    width: 100%;
    height: 100%;
    justify-content: space-between;
    padding: 20px;
    color:black;
} 
.navbar{
    position: absolute;
    top: 0;
    left: 0; 
    display: flex;
    width: 100%;
    justify-content: flex-end;
    padding: 20px;
    color:black;
} 
.barre_nav{
    display: flex ;
    align-items: center;
}
.barre_nav li{
    margin : 0 30px;
}
.barre_nav img {
    margin-top: 0%;
    height: 100px;
    width: 100px;
    left: 0%;
}

header {
    width : 100vw;
    height : 100vh;
    background-image: url('./Image/6506569.webp');
    background-position: bottom;
    background-size: cover;
    justify-content: center;
    display: flex;
    align-items:center;
    flex-direction: column;
    margin-top: 0%;
}
.header-content {
    margin-bottom: 150px;
    color:rgba(10, 10, 10, 0.932);
    text-align: center;
}
.header-content h1 {
    font-size: 4vmin;
    margin-top: 0%;
    
}
.header-content h4{
    color: black; 
    margin-top: 0px;
}

.line{
    width: 150px;
    height : 4px;
    background: #1c03fc;
    margin: 10px auto;
    border-radius: 5px;
}
.header-content h1{
    font-size: 7vmin;
    margin-top: 50px;
    margin-bottom: 30px;
}

.ctn{
    padding: 8px 15px;
    font-size: 22px;
    position: relative;
    bottom: -20px;
    background: #1c03fc;
    border-radius: 40px;
    color: whitesmoke; 
}
.menu-btn{
    position: absolute;
    top: 30px;
    right:30px;
    width :40px;
    cursor: pointer;
    display : none;
}
/* Histoire */

.histoire{
    width : 100vw;
    height : 100vh;
    background-image: url(6506569.webp);
    background-position: bottom;
    background-size: cover;
}

.title {
    text-align: start;
    padding : 1em;
    font-size: 4vmin;
    color: #582900;
    margin-top: 0%;
}
.row{
    display: flex;
    align-items: center;
    width :100%;
    justify-content: space-between;

}
.row .col{ 
    display: flex;
    flex-direction: column;
    align-items: center;

}
.histoire .row{
    margin-top: 40px;
    
}
.histoire .col img{
    margin: 0 27px;
    display: flex;
    justify-content: space-between;
}
.histoire .title .h1{
    margin-top: 15 vmin;
    left:50%;
}
h4{
    font-size: 3vmin;
    color:black;
    margin : 20px auto;
    font-weight: bold;
}
p{
    color: black;
    padding: 0px 40px; 
}
.histoire .ctn {
    margin-top: 20px ;
}

.explore{
    width : 100%;
    height : 100vh;
    background-image: url('6506569.webp');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    display : flex;
    align-items: center;
}
.explore-content{
    width: 100%;
    padding: 0px 40px;
    color: black;
    display : flex;
    align-items: center;
    flex-direction: column;
}
.explore-content h1{
    font-size: 7vmin;
}
.explore-content .line{
    margin-bottom: 40px;
}
.explore-content p{
    color: black;
}
.explore-content .ctn {
    margin-top: 40px;
}
/* MOBILE */

@media only screen {
    .menu-btn{
        display: block;
    }
    .navbar{
        padding: 0;
        color: whitesmoke;
    }
    .logo {
        position: absolute;
        top: 30px;
        left:30px;
    }
    .barre_nav{
        flex-direction: column;
        width: 100%;
        height: 100vh;
        justify-content: center;
        background-image: url(./Image/FondCG.avif);
        color: whitesmoke;
        margin-top: -1000px;
        transition: all 0.5s ease;
    }
    .mobile-menu{
        margin-top: 0px;
        border-bottom-right-radius: 0%;
    }
    .barre_nav li{
        margin: 50px auto; 
        color: whitesmoke;
    }
    .ll {
        width: 80%;
    }
    .histoire{
    height : 350vw;
}
}

/* . Histoire */
.row {
    flex-direction: column ;
}
.row .col{
    margin: 10px auto;
}
.row .col h1{
    margin-top: 0%;
}
.col img {
    max-width: 90%;
}

/* Explore */
.explore-content{
    width: 100%;
}

/* Animation */

img {
    transition: transform .3s ease;
}
img:hover {
    transform: scale(1.3);
}
.ctn:hover{
    background:whitesmoke ;
    color :#1c03fc;
    box-shadow: 2px 2px 5px black;
}

li:hover {
    color:#1c03fc;
    cursor: zoom-out;
}
