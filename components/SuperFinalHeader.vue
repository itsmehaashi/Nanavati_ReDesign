<template>
  <v-card>
    <v-toolbar
      color="purple"
      dark
      flat
      prominent
    >
    <VuetifyLogo/>
    
    <v-row>
    
    <v-spacer></v-spacer>
     <v-btn class="ma-8"  tile color="grey" dark >Quick Enquiry>></v-btn>
     <v-btn class="ma-8" tile color="deep purple" dark>Book Appointment</v-btn> 
      <v-divider vertical> </v-divider>
          <v-btn class="ma-8" tile color="grey" dark>Sign Up</v-btn>
     <v-btn class="ma-8" tile color="deep purple" dark>Sign In</v-btn>
    
</v-row>
    

      <template v-slot:extension>
      
        <v-tabs
          v-model="tabs"
          centered
        >
        <v-spacer> </v-spacer>
        
      <v-text-field
        append-icon="mdi-magnify"
        class="mx-4"
        flat
        hide-details
        label="Search"
        
        solo-inverted
      ></v-text-field>
        
          <v-tab> Outstation OPD</v-tab>
          <v-tab> International Patients</v-tab> 
          <v-tab> Doctors</v-tab> 
          
          
        </v-tabs>
        
      </template>
    </v-toolbar>
   
    
      

    <v-tabs-items v-model="tabs">
      <v-tab-item>
        <v-card flat>
          
        </v-card>
      </v-tab-item>
      <v-tab-item>
        
      </v-tab-item>
      <v-tab-item>
        
      </v-tab-item>
    </v-tabs-items>
  </v-card>
</template>

<script>
  export default {
    data () {
      return {
        tabs: null,
        text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',
      }
    },
  }
</script>