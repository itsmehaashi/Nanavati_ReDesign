  <template>
  
    <v-row justify="center" >
    
    
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
            <v-expansion-panel-header>Know Your Doctor</v-expansion-panel-header>
            
            <v-expansion-panel-content>
            <TransitionCardTrial/>
            
            
          
          </v-expansion-panel-content>
        </v-expansion-panel>

        
      </v-expansion-panels>
     
    </v-row>
    
  </template>
