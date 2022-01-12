<template>
<div >
  <v-app>
    <v-app-bar    
    >
      <v-img
        src="../assets/static/images/Jinkasan_Big_FT.png"
        max-height="316"
        max-width="166"
        contain
      ></v-img>
  
      <v-spacer></v-spacer>
        <v-toolbar-items>
          <v-btn depressed="depressed"> Accueil </v-btn>
          <v-btn depressed="depressed"> Q&A </v-btn>
          <v-btn depressed="depressed"> Qui sommes-nous? </v-btn>
          <v-btn depressed="depressed"> Contact </v-btn>
          <v-btn small> Se connecter <v-icon>mdi-menu-down</v-icon></v-btn>
        </v-toolbar-items>
  
    </v-app-bar>

    <v-container fluid class = "card-background">
    <v-row cols="8">
      <v-img
        src="../assets/static/images/Jinkasan_Services_Assurance.png">
      </v-img>
    </v-row>
    <v-row >
      <v-col md="4">
        <v-img
        class = "moto-img"
        src="../assets/static/images/Jinkasan_Moto.png">
      </v-img>
      </v-col>
      <v-col md="4">
        <v-img
        class = "moto-img"
        src="../assets/static/images/Jinkasan_Materiaux_Construction.png">
      </v-img>
      </v-col>
      <v-col md="4" >
        <v-img
        class = "moto-img"
        src="../assets/static/images/Jinkasan_Ordinateur.png">
      </v-img>
      </v-col>
      
    </v-row>
    
  </v-container>
  </v-app>

  
</div>
</template>

<script>
  export default {
  name: "HelloWorld",
  components: {},

  data() {
    return {
    }
  }
  }

</script>

<style scoped lang="scss">
  .card-background{
    top: 146px;
    left: 0px;
    width: 1920px;
    height: 947px;
    background: transparent linear-gradient(90deg, var(--unnamed-color-dc3a1e) 0%, var(--unnamed-color-ffcb00) 51%, var(--unnamed-color-3da25b) 100%) 0% 0% no-repeat padding-box;
    background: transparent linear-gradient(90deg, #DC3A1E 0%, #FFCB00 51%, #3DA25B 100%) 0% 0% no-repeat padding-box;
    opacity: 1;
  }
  .assurance-img{
    top: 100px;
    margin-left: 150px;
    width: 1200px;
    height: 291px;
    margin-right: 150px;
    box-shadow: 0px 3px 6px #00000029;
    opacity: 1;
  }
  /*.moto-img{
    width: 450px;
    height: 291px;
    margin-left: 140px;
    opacity: 1;
  }*/
</style>
