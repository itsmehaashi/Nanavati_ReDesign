<template>
  <v-row>
    <v-col cols="12" sm="4" offset-sm="5">
      <v-card>
        <v-toolbar color="light purple" light extended>
          <v-app-bar-nav-icon></v-app-bar-nav-icon>
          <!--Title-->
          <v-toolbar-title class="white--text">Lalitha's Patient profile</v-toolbar-title>
          <v-spacer></v-spacer>
          <v-btn icon>
            <v-icon>mdi-magnify</v-icon>
          </v-btn>
          <v-btn icon>
            <v-icon>mdi-view-module</v-icon>
          </v-btn>
          <template v-slot:extension>
            <v-btn
           <!--plus sign
              fab
              color="white"
              bottom
              left
              absolute
              @click="dialog = !dialog"-->
            >
              <v-icon>mdi-plus</v-icon>
            </v-btn>
          </template>
        </v-toolbar>
      <!-- Section 1 title-->
        <v-list two-line subheader>
          <v-subheader inset>Settings</v-subheader>

          <v-list-item v-for="item in items" :key="item.title" link>
            <v-list-item-avatar>
              <v-icon :class="[item.iconClass]">{{ item.icon }}</v-icon>
            </v-list-item-avatar>

            <v-list-item-content>
              <v-list-item-title>{{ item.title }}</v-list-item-title>

              <v-list-item-subtitle>{{ item.subtitle }}</v-list-item-subtitle>
            </v-list-item-content>

            <v-list-item-action>
              <v-btn icon>
                <v-icon color="grey lighten-6">mdi-information</v-icon>
              </v-btn>
            </v-list-item-action>
          </v-list-item>

          <v-divider inset></v-divider>
<!--section 2 title-->
          <v-subheader inset>Appointments</v-subheader>

          <v-list-item v-for="item in items2" :key="item.title" link>
            <v-list-item-avatar>
              <v-icon :class="[item.iconClass]">{{ item.icon }}</v-icon>
            </v-list-item-avatar>

            <v-list-item-content>
              <v-list-item-title>{{ item.title }}</v-list-item-title>

              <v-list-item-subtitle>{{ item.subtitle }}</v-list-item-subtitle>
            </v-list-item-content>
<!-- Info icons all-->
            <v-list-item-action>
              <v-btn icon ripple>
                <v-icon color="grey lighten-1">mdi-information</v-icon>
              </v-btn>
            </v-list-item-action>
          </v-list-item>
        </v-list>
<!-- Dialog box for plus sign-->
        <v-dialog v-model="dialog" max-width="500px">
          <v-card>
            <v-card-text>
              <v-text-field label="File name"></v-text-field>

              <small class="grey--text">* This doesn't actually save.</small>
            </v-card-text>

            <v-card-actions>
              <v-spacer></v-spacer>

              <v-btn text color="primary" @click="dialog = true">Submit</v-btn>
            </v-card-actions>
          </v-card>
        </v-dialog>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
  export default {
    data () {
      return {
        dialog: false,
        items: [
          {   src: 'Doc.jpeg' , title: 'Doctors', flex: '10' },
          { icon: 'folder', iconClass: 'grey lighten-1 white--text', title: 'Dashboard'  },
          { icon: 'folder', iconClass: 'grey lighten-1 white--text', title: 'Files' },
        ],
        items2: [
          { icon: 'assignment', iconClass: 'blue white--text', title: 'Missed' },
          { icon: 'call_to_action', iconClass: 'amber white--text', title: 'Scheduled' },
        ],
      }
    },
  }
</script>