
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
  <card url="https://images.rappi.com.mx/products/gp_mexican_torta_alemana.png?e=webp&d=800x800&q=80" nombre="Torta Alemana" nombre1="Jamón, chorizo, queso blanco." producto="Torta Alemana" costo="89"/>
  <card url="https://images.rappi.com.mx/products/gp_mexican_torta_rusa.png?e=webp&d=800x800&q=80" nombre="Torta Rusa" nombre1="Pierna española, milanesa, quesillo." producto="Torta Rusa" costo="89"/> 
  <card url="https://images.rappi.com.mx/products/gp_mexican_torta_hawaiana.jpg?e=webp&d=800x800&q=80" nombre="Torta Hawaiana" nombre1="Jamón de pavo, piña y quesillo." producto="Torta Hawaiana" costo="89"/>
  <card url="https://images.rappi.com.mx/products/gp_mexican_torta_pachuquena.jpeg?e=webp&d=800x800&q=80" nombre="Torta Pachuqueña"  nombre1="Milanesa de res, piña y quesillo." producto="Torta Pachuqueña" costo="89"/>
  <card url="https://images.rappi.com.mx/products/gp_mexican_torta_cubana.png?e=webp&d=800x800&q=80" nombre="Tprta Cubana" nombre1="Pierna ahumada, milanesa de res, salchicha, chorizo, huevo, queso blanco, queso amarillo, quesillo." producto="Torta Cubana" costo="110"/>
  <card url="https://images.rappi.com.mx/products/gp_mexican_torta_espanola.png?e=webp&d=800x800&q=80" nombre="Torta Española" nombre1="Jamón, queso amarillo y chorizo." producto="Torta Española " costo="89"/>
  <footerc>
  </footerc>
</body>
 
</template>

<style scoped>
nav{
  background-color: rgba(7, 7, 113, 0.838);
  color: white;
  font-size: 5vh;
  text-align: center;
  padding: 5px;
}

</style>
