<template>
  <v-container fluid>
    <v-row justify="center">
      <v-subheader>By our dear patients</v-subheader>

      <v-expansion-panels popout
      v-model="popout"
      light
      focusable
      tile
      single
      >
        <v-expansion-panel
          v-for="(message, i) in messages"
          :key="i"
          hide-actions
          
        >
         
          <v-expansion-panel-header>
            <v-row
              align="center"
              class="spacer"
              no-gutters
            >
            
              <v-col
                cols="4"
                sm="2"
                md="1"
              >
                <v-avatar
                  size="36px"
                >
                
                  <img
                    v-if="message.avatar"
                    alt="Avatar"
                    src=""
                    
                    
                  >
                  
                  
                  <v-icon
                    v-else
                    :color="message.color"
                    v-text="message.icon"
                    
                  ></v-icon>
                </v-avatar>
              </v-col>

              <v-col
                class="hidden-xs-only"
                sm="5"
                md="3"
              >
                <strong v-html="message.name"></strong>
                <span
                  v-if="message.total"
                  class="grey--text"
                >
                  &nbsp;({{ message.total }})
                </span>
              </v-col>

              <v-col
                class="text-no-wrap"
                cols="5"
                sm="3"
              >
         <v-icon small color="yellow accent-2"> mdi-star</v-icon>     
         <v-icon small color="yellow accent-2"> mdi-star</v-icon>
         <v-icon small color="yellow accent-2"> mdi-star</v-icon>
         <v-icon small color="yellow accent-2"> mdi-star-half</v-icon>
               <!-- <v-chip
                  v-if="message.new"
                  :color="`${message.color} lighten-4`"
                  class="ml-0 mr-2 black--text"
                  label
                  small
                >
                  {{ message.new }} new
                </v-chip>-->
                <strong v-html="message.title"></strong>
              </v-col>

              <v-col
                v-if="message.excerpt"
                class="grey--text text-truncate hidden-sm-and-down"
              >
                &mdash;
                {{ message.excerpt }}
              </v-col>
            </v-row>
          </v-expansion-panel-header>

          <v-expansion-panel-content>
            <v-divider></v-divider>
            <v-card-text v-text="lorem"></v-card-text>
          </v-expansion-panel-content>
        </v-expansion-panel>
      </v-expansion-panels>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    data: () => ({
      messages: [
        {
          avatar: 'https://avatars0.githubusercontent.com/u/9064066?v=4&s=460',
          name: 'Mrs.Anjali Pawar',
          title: '3/5',
          excerpt: '"Very Experienced and learned. A true...."',
        },
        {
          avatar: "rev-2.jpg",
          name: 'Mr. Nikhil Suryavanshi',
          title: '4',
          excerpt: '"One of the best hospital experiences. Every process went smooth...."',
        },
        {
          avatar: 'https://avatars0.githubusercontent.com/u/9064066?v=4&s=460',
          name: 'Mrs. Sheila Alexander',
          title: '3/5',
          excerpt: '"All doctors are the best in their fields and the...."',
        },
         
       
      ],
      lorem: 'The doctors are experts in their fields, who give their utmost priority to patients. Not only Doctors, but the whole staff aslo makes sure that the patient is at ease at all times. They have excellent facilitites and they truluy do take care.'
    }),
  }
</script>