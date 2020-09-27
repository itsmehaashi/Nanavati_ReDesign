<template>
<v-row>
<caption>
  <div>
    <v-breadcrumbs :items="items">
    <template v-slot:divider>
        <v-icon color="#757575">mdi-chevron-right</v-icon>
      </template>
      </v-breadcrumbs>

  </div>
  </caption>
  </v-row>
</template>

<script>
  export default {
    data: () => ({
      items: [
        {
          text: 'Home Page',
          disabled: false,
          href: 'breadcrumbs_dashboard',
        },
        {
          text: 'Treatment & Specialities',
          disabled: false,
          href: 'breadcrumbs_link_1',
        },
        {
          text: 'Specialty Centre',
          disabled: false,
          href: 'breadcrumbs_link_2',
        },
         {
          text: 'Neuro-Endoscopy Treatment Unit',
          disabled: false,
          href: 'breadcrumbs_link_2',
        },
      ],
    }),
  }
</script>