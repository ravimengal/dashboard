<template>
  <v-app :style="{background: $vuetify.theme.themes.light.background}">
    <v-layout row>
      <v-flex >
        <v-app :style="{background: $vuetify.theme.themes.dark.background}" class="rounded-tr-xl rounded-br-xl">
         
          <v-container>
             <v-col cols="12" sm="12">
             <v-navigation-drawer cols="12">Navigation bar</v-navigation-drawer>
             </v-col>
              <v-row>
                <v-col cols="12" sm="12">
                  <v-app-bar color="rgba(0,0,0,0)" flat class="mx-8 mb-8 mt-3">
                    <v-text-field
                    prepend-icon="mdi-magnify"
                    color="teal"
                    placeholder="search ticket"
                    flat
                    success 
                  ></v-text-field>
                  </v-app-bar>
                </v-col>
              </v-row>
          </v-container>
        </v-app>
      </v-flex>
      
    </v-layout>
  </v-app>
</template>
<script>
export default {
 
  
};
</script>
<style scoped>

</style>
