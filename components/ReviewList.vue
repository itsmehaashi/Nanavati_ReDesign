 <template>
  <div>
  <!--1st-->
    <v-list
      class="mx-auto"
      max-width="1600px"
        :flat="flat"
        :dense="dense"
      > "Very Experienced and learned. A true expert in his field"
         ~Mrs. Subha Nair
      </v-list>
<!--2nd-->
       <v-list
      class="mx-auto"
      max-width="1600px"
        :flat="flat"
        :dense="dense"
      > "All doctors are the best in their fields and the facilities are excellent."
        ~Mr. Digvijay Sahai
      </v-list>
    <!--3rd-->
    <v-list
      class="mx-auto"
      max-width="1600px"
        :flat="flat"
        :dense="dense"
      > "One of the best hospital experiences. Every process went smoothly for my husband and I"
      ~Mrs. Rimmi Mathur
      </v-list>
<!--4th-->
      <v-list
      class="mx-auto"
      max-width="1600px"
        :flat="flat"
        :dense="dense"
      > "The Hospital is not negligent when it comes to taking care of patients. Really good experience'"
      ~Mrs. Meera Rai
      </v-list>
  </div>
</template>

<script>
  export default {
    data: () => ({
      item: {
        icon: 'mdi-graduation-cap',
        text: 'Wifi',
      },
      model: 1,
      multiple: false,
      mandatory: false,
      flat: false,
      dense: false,
      count: 4,
    }),
  }
</script>