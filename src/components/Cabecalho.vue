<script>
//
</script>

<template>
  <div class="cabecalho">
    <v-toolbar dark prominent color="black" >
      <img src="../../public/logo-favicon2.png" style="max-width: 80px;">
      <v-toolbar-title class="red--text">DigiStore</v-toolbar-title>



      <v-text-field hide-details prepend-icon="mdi-magnify" single-line size="60%"
        placeholder="Pesquisar..."></v-text-field>
      <v-spacer></v-spacer>


      <v-row>
        <v-col cols="12" sm="2">
          <v-toolbar-title>Vender</v-toolbar-title>
        </v-col>
        <v-spacer></v-spacer>
        <v-col cols="12" sm="3">
          <v-toolbar-title>Carrinho</v-toolbar-title>
        </v-col>
        <v-col cols="12" sm="2">
          <v-toolbar-title>Entar</v-toolbar-title>
        </v-col>
        <v-col cols="12" sm="3">

          <v-toolbar-title>Registrar</v-toolbar-title>
        </v-col>
      </v-row>





      <v-btn icon>
        <v-icon>mdi-export</v-icon>
      </v-btn>
      

    </v-toolbar>




  </div>
</template>

<style>
.red--text {
  color: rgba(90, 237, 131, 1)
}
</style>