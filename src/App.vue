
<script>
  import Card from "./components/Card.vue"
  import headercard from "./components/headercard.vue"
  import footerc from "./components/footerc.vue"

  export default {
    components:{Card,
      headercard,
      footerc
    },
  };
</script>

<template>
    <headercard>
    </headercard>
<body>
  <nav>Menú</nav>
  <div class="card p-3 bg-transparent">
  </div>

  <div class="contenedor">
    <card url="https://www.bellaburguesa.es/wp-content/uploads/2017/01/PERRITO_result13.png"
    nombre="PERRITO ESPECIAL CON BACON"
    detalles="Salchicha de Vacuno, Ketchup, Mostaza, Bacon y Cebolla crujiente."
    precio="4,00" />
<card url="https://www.bellaburguesa.es/wp-content/uploads/2017/01/BUEY_result39-400x400.png"
    nombre="BURGUES BUEY 180GR."
    detalles="Carne de Buey, Lechuga, Tomate, Cebolla, Queso y Bacon."
    precio="8,50" />  
<card url="https://www.bellaburguesa.es/wp-content/uploads/2017/01/GAJO_result24-510x510.png"
    nombre="PATATAS GAJO PEQUEÑA."
    detalles="Patatas en gajo, pequeñas."
    precio="2,50" />
<card url="https://www.bellaburguesa.es/wp-content/uploads/2017/01/ALITAS_result44.png"
    nombre="ALITAS"
    detalles="Alitas con aderesos para comparir."
    precio="4,50" /> 
<card url="https://www.bellaburguesa.es/wp-content/uploads/2017/01/CLUB-BELLA_result32.png"
    nombre="CLUB BELLA."
    detalles="Jamón York, Queso, Pollo, Tomate, Lechuga, Mahonesa y Huevo Frito."
    precio="7,00" />
<card url="https://www.bellaburguesa.es/wp-content/uploads/2018/06/HELADO_result23.png"
    nombre="HELADO"
    detalles="Helado de Turrón y Caramelo."
    precio="2,50" />
</div>
  <footerc>
  </footerc>
</body>
 
</template>

<style scoped>
nav{
  background-color: rgba(94, 113, 7, 0.838);
  color: white;
  font-size: 5vh;
  text-align: center;
  padding: 5px;
}

</style>
