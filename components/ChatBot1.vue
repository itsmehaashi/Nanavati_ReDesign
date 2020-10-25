<template v-slot:activator>
<!--unactivated//alignment and color-->
        <v-btn
          v-model="fab"
          color="pink darken-4"
          dark
          fab
        >
          <v-icon v-if="fab">mdi-close</v-icon>
          <v-icon v-else>mdi-account-circle</v-icon>
        </v-btn>
      </template>