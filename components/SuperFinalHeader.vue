<template>
  <v-card>
    <v-toolbar
      color="grey lighten-4"
      dark
      flat
      prominent
    >
    <v-row>
    <v-col cols="12" sm="2" md"4">
    <VuetifyLogo/>
     <!--<strong class="black--text ">
    <p class="text-right">
    Patient Portal
    </p>
    </strong> -->
    </v-col>
    </v-row>
    <!--Buttons start here-->
    <v-row>
    

    
     <v-col cols="12" md="3" sm="5"> <v-btn tile color="pink darken-4" dark > <strong class="white--text ">Quick Enquiry>></strong></v-btn></v-col> 
     <v-col cols="12" md="4"sm="7"><v-btn tile color="white" dark> <strong class="pink--text text--darken-4 ">Book Appointment</strong></v-btn></v-col> 
      <v-divider vertical
      color="grey" 
      class= "hidden-xs-only"
      >
      </v-divider>
      <v-col cols="12" sm="3"> <strong class="black--text ">Patient Portal </strong></v-col>
     <v-col cols="12" md="2" sm="3"><v-btn  tile color="pink darken-4" dark><strong class="white--text ">Sign Up </strong></v-btn></v-col>
     <v-col  cols="12"md="1" sm="5"><v-btn  tile color="white" dark> <strong class="pink--text text--darken-4 ">Sign In</strong></v-btn></v-col>
    
</v-row>
   <!--Buttons end here--> 

      <template v-slot:extension>
      
        <v-tabs
          v-model="tabs"
          
          class="pa-mx-12 "
        >
       <!--3 tabs nav bar starts here--> 
        <v-spacer> </v-spacer>
        
        
          <v-tab>  <strong class="black--text ">Outstation OPD </strong></v-tab>
          <v-tab> <strong class="black--text ">International Patients</strong></v-tab> 
          <v-tab> <strong class="black--text ">Doctors</strong></v-tab> 
          
          
        </v-tabs>
        
<!--search bar-->
        <v-text-field
        append-icon="mdi-magnify grey lighten-1"
        class="grey darken-1"
        flat
        hide-details
        label="Search"

        solo-inverted
      >
      </v-text-field>
     
        
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