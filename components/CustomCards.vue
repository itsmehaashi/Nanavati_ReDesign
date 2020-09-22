 <template>
  <v-card
    class="mx-0 pa-0"
    max-width="344"
    color="light grey"
  >
    <v-img
      src="Oak.jpg"
      height="200px"
    ></v-img>

    <v-card-title>
      Dr.Pradyuman Oak
    </v-card-title>

    <v-card-subtitle>
     Director & Head, Neurosurgery 
    </v-card-subtitle>

    <v-card-actions>
      <v-btn text>Share</v-btn>

      <v-btn
        color="purple"
        text
         
      >
        Explore
      </v-btn>

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
      show: false,
    }),
  }
</script>