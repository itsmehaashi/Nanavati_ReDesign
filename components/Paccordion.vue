  <template>
  <!--3rd accordion start-->
    <v-row justify="center">
    <!--bolean-->
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
            <Avatars/>
            
            
          
          </v-expansion-panel-content>
        </v-expansion-panel>

        
      </v-expansion-panels>
    </v-row>
  </template>

