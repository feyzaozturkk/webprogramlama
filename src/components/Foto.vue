<template>
<v-app>
  <v-content>

  <v-carousel  class="fill-height about" fluid  >

           <v-card  class="elevation-12 ml-15 mt-7 " color="#FFFFF" height="900px" width="1400px">



    <v-carousel-item  
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      
        ></v-carousel-item></v-card>
      </v-carousel>
  </v-content>
 </v-app>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'https://www.pelininayakkabilari.com/Uploads/Slider/-87.jpg?t=20200904182826',
          },
          {
            src: 'https://www.pelininayakkabilari.com/Uploads/Slider/-90.jpg?t=20201031151430',
          },
         
        ],
      }
    },
  }
</script>

<style scoped>

</style>