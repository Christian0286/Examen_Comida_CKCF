<template>
    <header>
    <h1>Comida Rapida</h1>
    <button onclick="window.open('https://www.bellaburguesa.es/')">Ordene aquì</button>
</header>
</template>
<script>

</script>

<style>
    @font-face {
        font-family: 'Bungee Spice', cursive;
        src: url("https://fonts.googleapis.com/css2?family=Bungee+Spice&family=Poppins:ital,wght@0,100;0,300;1,200&display=swap");
    }
header{
    background-image: url("https://www.bellaburguesa.es/wp-content/uploads/2016/12/AW87B2945.jpg");
    background-size:cover;
    background-repeat: no-repeat;
    height: 60vh;
    display: block;
    text-align: center;
}
h1{
    padding-top: 30vh;
    padding-bottom: 20px;
    color: rgb(0, 0, 0);
    font-family: 'Bungee Spice', cursive;
    font-size: 10vh;
}
button{
    text-decoration: none;
    font-size: 25px;
    color:rgb(0, 248, 21);
    padding: 10px;
    border: solid white 1px;
    border-radius: 10px;
    font-family: 'Bungee Spice';
    background:transparent;
}
</style>