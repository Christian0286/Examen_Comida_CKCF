<template>
       
    <div>
<img :src="url" alt="nombre">
<h2 class="mt-1">{{ nombre }}</h2>
<p>{{detalles}}</p>
<p class="text-secondary">{{precio}} €</p>
</div>
</template>
<script>
export default{
props:{
url:{
    String,
},
nombre:{
    String,
},
detalles:{
    String,
},
precio:{
    Number,
},
},
};
</script>
<style scoped>
div{
padding:10px;
border: solid 1px;
width: 24%;
margin: 5px;
border-radius: 5px;
text-align: center;
display: inline-block;

}

div img{
width: 100%;
}
a{
text-decoration: none;
}
body{
width: 100%;
}

@media screen and (max-width: 850px){
div{
padding:10px;
border: solid 1px;
width: 40%;
margin: 5px;
border-radius: 5px;
justify-content: center;

}

}

@media screen and (max-width: 380px){
div{
padding:10px;
border: solid 1px;
width: 100%;
border-radius: 5px;
justify-content: center;    
}   

}

</style>