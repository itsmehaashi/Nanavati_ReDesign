<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">
    
    <!--Header -->
    <NVTab/>
    <Breadcrumb/>
    <v-app-bar color= "Light purple" dark fixed app>
      <v-toolbar-title></v-toolbar-title>
       <!-- Component Example -->
       
      <VuetifyLogo/>
     
    </v-app-bar>

    <!-- Body -->
    <v-content light>
      <nuxt /> 
    </v-content>
    
    <!-- Footer -->
    <v-footer color="Light purple" app>
      <span class="white--text">&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>

  </v-app>
</template>

<script>
export default {}
</script>

<style> 
  .white--text {
    border: 1px solid;
  }

   #inspire {
    background-color: white;
    color: white;
  }
</style>