 <template>
  <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-4 pa-0"
       max-width="330"
      color="white"
    >
      <v-img
        :aspect-ratio="8/9"
        src="Oak.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey darken-1 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr. Pradyuman Oak</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2">Director & Head Neurosurgery</div>
        
      </v-card-text>
    </v-card>
  </v-hover>

  <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-4 pa-0"
       max-width="330"
      color="white"
    >
      <v-img
        :aspect-ratio="8/9"
        src="Oak.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey darken-1 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr. Pradyuman Oak</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2">Director & Head Neurosurgery</div>
        
      </v-card-text>
    </v-card>
  </v-hover>

  
</template>

<style>
.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: .5;
  position: absolute;
  width: 100%;
}
</style>