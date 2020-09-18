<template>
  <div>
    <v-breadcrumbs :items="items"></v-breadcrumbs>

  </div>
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
          disabled: true,
          href: 'breadcrumbs_link_2',
        },
      ],
    }),
  }
</script>