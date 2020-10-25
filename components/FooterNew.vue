<template>
<!--used-->
  <v-footer
    dark
    padless
  ><!--footer color changed here-->
    <v-card
      flat
      tile color="pink darken-4"
      dark
      class="pink darken-4 white--text text-center"
    >
    <!--main footer content do not delete//add li-->
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4"
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-1">
        Dr. Balabhai Nanavati Hospital, S.V. Road, Vile Parle (West), Mumbai 400 056, India.
Tel:+91 22 6836 0000
24 Hrs helpline: +91 22 2626 7500
Email:marketing@nanavatihospital.org
Stay connected on Social Media : Instagram, Facebookt, Twitter, Email us 24x7 helpline
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong></strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>