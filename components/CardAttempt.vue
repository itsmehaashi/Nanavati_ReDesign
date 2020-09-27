 <template>
  <v-card
    class="mx-0 pa-0"
    max-width="344"
    color="white"
  >
  
  <v-card-title>
  <p class="text--end">
       <span class="pink accent-4--text" 
       > Dr.Pradyuman Oak </span>
     </p>   
    </v-card-title>
    
    

    <v-card-subtitle>
     Director & Head, Neurosurgery 
    </v-card-subtitle>

    <v-img
      src="Oak.jpg"
      height="310px"
    ></v-img>

    
      <v-row>
     <!--More dialogue starts here-->
      <v-btn
        color="purple"
        text
        @click.stop="dialog = false"
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
            @click="dialog = true"
          >
            OK
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
     </v-row>
   <!--More dialog ends here-->
        

      <v-spacer></v-spacer>

      <v-btn
        icon
        @click="show = !show"
      >
        <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
      </v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show">
        <v-divider></v-divider>
        Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
        <v-card-text>
          
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
</template>

<script>
  export default {
    data: () => ({
      show: true,
    }),
  }
</script>