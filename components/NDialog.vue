<template>
  <v-row justify="bottom">
    <v-btn
      color="purple"
      dark
      width="50"
      @click.stop="dialog = true"
    >
      MORE
    </v-btn>

    <v-dialog
      v-model="dialog"
      max-width="390"
    >
      <v-card>
        <v-card-title class="headline">Qualifications</v-card-title>

        <v-card-text>
         Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </v-card-text>

        <v-card-actions>
          <v-spacer></v-spacer>

         
          <v-btn
            color="green darken-1"
            text
            @click="dialog = false"
          >
            OK
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </v-row>
</template>

<script>
  export default {
    data () {
      return {
        dialog: false,
      }
    },
  }
</script>