<template>
<v-container>
  <v-layout align-center justify-center row>
   
  <v-card 
    v-for="(personaje, id) in personajes"
    :key="id"
    class="mx-auto card-vue"
    max-width="344"
  >
    <v-img
      :src="personaje.imagen"
      height="200px"
    ></v-img>
    <v-card-title>
     {{personaje.nombre}}
    </v-card-title>
  </v-card>
  
  </v-layout>
</v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data: () => ({
      personajes: [
        {
        'id': 1,
        'nombre': 'Morty',
        'imagen':
        'https://rickandmortyapi.com/api/character/avatar/2.jpeg'
        },
        {
        'id': 2,
        'nombre': 'Rick',
        'imagen':
        'https://rickandmortyapi.com/api/character/avatar/1.jpeg'
        },
        {
        'id': 3,
        'nombre': 'Summer',
        'imagen':
        'https://rickandmortyapi.com/api/character/avatar/3.jpeg'
        },
        {
        'id': 4,
        'nombre': 'Beth',
        'imagen':
        'https://rickandmortyapi.com/api/character/avatar/4.jpeg'
        },
        {
        'id': 5,
        'nombre': 'Jerry',
        'imagen':
        'https://rickandmortyapi.com/api/character/avatar/5.jpeg'
        },
        {
        'id': 6,
        'nombre': 'Morty',
        'imagen':
        'https://rickandmortyapi.com/api/character/avatar/2.jpeg'
        },
  ]   
    })
  }
</script>

<style scoped>
.card-vue{
  margin-top: 30px;
}
</style>