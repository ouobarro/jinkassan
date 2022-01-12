<template>
  <div>
    <v-app>
      <v-app-bar>

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

      <v-container fluid class="cardBackground">
        
        <v-row class="mt-15 pl-15 pr-15">
          <div>
            <h1 class="white--text">
              Notre service d'assurance auto groupée 
            </h1>
            <h5 class="white--text">
              Intégrez la plus grande flotte d'assurance auto au Burkina
            </h5>
          </div>
          
          <v-img src="../assets/static/images/Jinkasan_Services_Assurance.png">
          </v-img>
        </v-row>
        <div class="mt-10 pl-12">
            <h1 class="white--text">
              Notre service d'assurance auto groupée 
            </h1>
            <h5 class="white--text">
              Intégrez la plus grande flotte d'assurance auto au Burkina
            </h5>
          </div>
        <v-row class="mb-15 pl-12 pr-12">
          <v-col md="4">
            <v-img
              class="moto-img"
              src="../assets/static/images/Jinkasan_Moto.png"
            >
            </v-img>
          </v-col>
          <v-col md="4">
            <v-img
              class="moto-img"
              src="../assets/static/images/Jinkasan_Materiaux_Construction.png"
            >
            </v-img>
          </v-col>
          <v-col md="4">
            <v-img
              class="moto-img"
              src="../assets/static/images/Jinkasan_Ordinateur.png"
            >
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
    return {};
  },
};
</script>

<style scoped lang="scss">
.cardBackground {
  top: 146px;
  left: 0px;
  width: 1920px;
  height: 947px;
  background: transparent
    linear-gradient(
      90deg,
      var(--unnamed-color-dc3a1e) 0%,
      var(--unnamed-color-ffcb00) 51%,
      var(--unnamed-color-3da25b) 100%
    )
    0% 0% no-repeat padding-box;
  background: transparent
    linear-gradient(90deg, #dc3a1e 0%, #ffcb00 51%, #3da25b 100%) 0% 0%
    no-repeat padding-box;
  opacity: 1;
}
</style>
