<template>
  <!--Your App Starts Here -->
  <v-app id="inspire">

    
    <!--Header -->
    
    
  >
  
   <SuperFinalHeader/>
    
    
   
      <v-toolbar-title>
    </v-toolbar-title>
       <!-- Component Example -->
       
      
     
    </v-app-bar>

    <!-- Body -->
    <v-content light>
      <nuxt /> 
    </v-content>
    
    <!-- Footer -->
    <ChatBot1/> 
    <v-speed-dial
      v-model="fab"
      :top="top"
      :bottom="bottom"
      :right="right"
      :left="left"
      :direction="direction"
      :open-on-hover="hover"
      :transition="transition"
    >
    </v-speed-dial>
    
    
    <template>
 <!-- <v-footer
    dark
    padless
  >
  
    <v-card
      flat
      tile
      class="pink darken-4 white--text text-center"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4 white--text"
          icon
        >
          <v-icon size="24px">{{ icon }}</v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
       Dr. Balabhai Nanavati Hospital, S.V. Road, Vile Parle (West), Mumbai 400 056, India.Tel:+91 22 6836 0000.24 Hrs helpline: +91 22 2626 7500.Email:marketing@nanavatihospital.org.About Nanavati Hospital. Leeadership.Newsroom. Contact us- Instagram, twitter.




      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong></strong>
      </v-card-text>
    </v-card>
    </v-card>
  </v-footer>-->
  <FooterNew/>
</template>

<script>
  export default {
    data: () => ({
      icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],
    }),
  }
</script>

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