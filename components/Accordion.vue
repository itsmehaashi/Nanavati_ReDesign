<template>
  <v-row justify="center">
    <v-expansion-panels accordion>
      <v-expansion-panel
        v-for="(Item,i) in 5"
        :key="i"
      >
        <v-expansion-panel-header>Food</v-expansion-panel-header>
        
        <v-expansion-panel-content>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </v-expansion-panel-content>
      </v-expansion-panel>

       <v-expansion-panel
        v-for="(Item,i) in 5"
        :key="i"
      >
        <v-expansion-panel-header>Neuro</v-expansion-panel-header>
        <v-expansion-panel-content>
Neuroendoscopy is a brain tumor surgery offered by the Hospital
        </v-expansion-panel-content>
      </v-expansion-panel>
    </v-expansion-panels>
  </v-row>
</template>
