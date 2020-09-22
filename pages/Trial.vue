<template>
<v-container>

<Blockquote/>
    <v-row
    no-gutters
    >
    <v-col
    v-for="i in 3"
    :key=i
    cols="12"
    md="4"
    >
      <v-responsive
      class="text-center grey lighten-2 rounded-circle d-inline-flex align-center justify-center ma-3"
      height="64"
      width="64"
    >
      Circle
    </v-responsive>
    </v-col>
    </v-row>
  <v-row
    
    >
    <v-col
    
    
    >
      <v-responsive
      class="text-center grey lighten-2 rounded-pill d-inline-flex align-center justify-center ma-3"
      height="64"
      width="128"
    >
      Pill
    </v-responsive>
    </v-col>
     <v-col
     
    
    >
<v-responsive
      class="text-center grey lighten-2 rounded-pill d-inline-flex align-center justify-center ma-3"
      height="64"
      width="128"
    >
      Pill
    </v-responsive>
    </v-col>
    </v-row>
</v-container>
  </template
