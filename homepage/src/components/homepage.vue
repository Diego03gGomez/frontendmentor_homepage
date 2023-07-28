<template lang="">
    <div>
<div class="cont_oculto ocultar">

    <div class="menu_oculto ">
        <i v-on:click="cerrar_menu()" class="fa-solid fa-xmark cerrar"></i>
    <a href="">Home</a>
    <a href="">New</a>
    <a href="">Popular</a>
    <a href="">Trending</a>
    <a href="">Categories</a>
    </div>


</div>


        


        <header>
<div class="cont_header">
    <h1><img src="https://ryusuke66.github.io/news-homepage-main/assets/images/logo.svg" alt=""></h1>

<nav>
    <a href="">Home</a>
    <a href="">New</a>
    <a href="">Popular</a>
    <a href="">Trending</a>
    <a href="">Categories</a>
</nav>

<i v-on:click="mostrar_menu()" class="fa-solid fa-bars icono"></i>
</div>

        </header>


<div class="cont_fondo1">


<div class="columna1">
<div class="div1"><img src="https://ryusuke66.github.io/news-homepage-main/assets/images/image-web-3-desktop.jpg" alt=""></div>
<div class="div2">

<div class="div2_1"><h1>The Bright <br>
Future of <br> Web 3.0?</h1></div>
<div class="div2_2">
<p>We divide into the next evolution of the web that <br>
claims to put the power of the plattaforms back <br>
into the hands of the people. But is it really <br>
fulfilling its promise?</p>

<a>READ MORE</a>

</div>
</div>
</div>


<div class="columna2">
<h1>New</h1>

<div class="cont_columna2">
    <h3>Hydrogen VS Electric Cars</h3>
    <p>Will hydrogen-fueled cars ever catch up to <br>
    EVs?</p>
    <hr>
</div>

<div class="cont_columna2">
    <h3>The Downsides of AI Artistry</h3>
    <p>What are the possible adverse effects of <br>
        on-demand AI image generation?</p>
    <hr>
</div>


<div class="cont_columna2">
    <h3>Is VC Funding Drying Up?</h3>
    <p>Private funding by VC firms is down 50% <br>
        YOY. We take a look at what that means.</p>
    <hr>
</div>

</div>

</div>


<div class="cont_cards">
<div class="card">
    <div class="img_card">
        <img src="https://ryusuke66.github.io/news-homepage-main/assets/images/image-retro-pcs.jpg" alt="">
    </div>
    <div class="des_card">
        <h2>01</h2>
    <h3>Reviving Retro PCs</h3>
    <p>What happends when old PCs are given <br>
    modern upgrades?</p>
    </div>
    
</div>

<div class="card">
    <div class="img_card">
        <img src="https://ryusuke66.github.io/news-homepage-main/assets/images/image-top-laptops.jpg" alt="">
    </div>
<div class="des_card">
    <h2>02</h2>
    <h3>Top 10 Laptops of 2022</h3>
    <p>Our best picks for various needs <br>
    and budgets</p>
</div>
</div>

<div class="card">
    <div class="img_card">
        <img src="
https://ryusuke66.github.io/news-homepage-main/assets/images/image-gaming-growth.jpg" alt="">
    </div>
<div class="des_card">
    <h2>03</h2>
    <h3>The Growth of Gamming</h3>
    <p>How the pandemic, has sparked fresh<br>
    opportunities.</p>
</div>
</div>



</div>


    </div>
</template>
<script>
export default {
methods: {
    cerrar_menu() {
        let menu = document.querySelector(".cont_oculto");
        menu.classList.remove("mostrar")
    },
    mostrar_menu(){
     let menu = document.querySelector(".cont_oculto");
     menu.classList.add("mostrar")   
   
    }
},

    
}
</script>
<style lang="">
    
</style>