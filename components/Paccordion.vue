  <template>
    <v-row justify="center">
      <v-expansion-panels accordion
      v-model="panel"
      light
      focusable
      tile
      single
      >
      
        <v-expansion-panel
        
        >
          <!--Know your doctor accordion starts-->
            <v-expansion-panel-header>Patient reviews</v-expansion-panel-header>
            
            <v-expansion-panel-content>
            <ReviewList/>
            
            
          
          </v-expansion-panel-content>
        </v-expansion-panel>

        
      </v-expansion-panels>
    </v-row>
  </template>

