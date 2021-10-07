<template>
  <v-footer padless class="footer">
    <v-col
      class="text-center"
      cols="12"
    >
      {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
    </v-col>
  </v-footer>
</template>


<script>
export default {
    name: 'Footer',
};
</script>

<style lang="scss" scoped>
.footer{
    margin-top: 40px;
}
</style>