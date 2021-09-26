<template>
  <container>
    <login></login>
    <v-row class="text-center">
      <v-col >
         <br>
          <br>
          <br>
          <br>
        <h2>Software Para el Control de Vencimientos</h2>
          <br>
            <br>
              <br>
          <p justify="center">
          Aplicación web con alertas tipo semáforo su proposito es generar notificaciones 
          periodicas y constantes segun el requerimiento que maneja cada producto que comercializa la compañia.  
          </p>
          <br>
            <br>
              <br>
                <br>
                  <br>
          <p justify="center">
          Ingresa tu usuario y contraseña, Comienza a supervisar los producros de tu establecimiento
          </p>
     
      </v-col>
      
       <v-col class="text-center">
         <img  alt="Software logo" src="../assets/Logo.png" height="200px" width="200px" >
         <v-row class="text-center">
         </v-row>
        Derecha
      </v-col>
      </v-row>
  
    
  </container>
  
</template>

<script>
import Login from '../components/Login.vue'
export default {
  components: { Login },

}
</script>

<style>

</style>
