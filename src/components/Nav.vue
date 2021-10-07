<template>
<div>
    <v-app-bar
      color="#fcb69f"
      dark
    >     
     <v-toolbar-title>Mi App</v-toolbar-title>
         <v-spacer></v-spacer>
        <v-toolbar-title class="title">Inicio</v-toolbar-title>
        <v-toolbar-title class="title">Buscar</v-toolbar-title>
       <v-toolbar-title class="title">Acerca de</v-toolbar-title>
    </v-app-bar>
</div>
</template>
<script>
export default {
    name: 'Nav',
};
</script>

<style lang="scss" scoped>
.title{
    margin-right: 10px;
}
</style>