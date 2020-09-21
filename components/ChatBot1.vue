<template v-slot:activator>
        <v-btn
          v-model="fab"
          color="purple"
          dark
          fab
        >
          <v-icon v-if="fab">mdi-close</v-icon>
          <v-icon v-else>mdi-account-circle</v-icon>
        </v-btn>
      </template>