<template>
<v-container fluid>
    
<v-row justify="center">
 <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0"
       width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Oak.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4"><h2>Dr. Pradyuman Oak</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2">Director & Head Neurosurgery</div>
        
      </v-card-text>
    </v-card>
  </v-hover>
  
  <!--Neeta-->
 <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Neeta.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr.Neeta Shah</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2"> Consultant-Neurosurgery</div>
        
      </v-card-text>
    </v-card>
  </v-hover>

<!--Rajan-->

<v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Rajan.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr.Rajan Shah</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2"> Director & Head-Neurosurgery</div>
        
      </v-card-text>
    </v-card>
  </v-hover> 

<!--Sawant-->
  <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Sawant.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr.Bapujee Sawant</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2"> Consultant-Neurosurgery</div>
         </v-card-text>
    </v-card>
  </v-hover>
  <!--2nd row-->
  <!--Abhishek-->

<v-row justify="center">
  <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Abhishek.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr.Abhishek A. Karadkar</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2"> Consultant Spine Surgeon (Minimally invasive & Endoscopy specialist)</div>
         </v-card-text>
    </v-card>
  </v-hover>
<!--Amandeep-->
<v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Amandeep.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr. Amandeep Gujral</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2"> Consultant - Nanavati Institute of Spine Surgery</div>
         </v-card-text>
    </v-card>
  </v-hover>
<!--KC-->
  <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="KC.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr. K.C. Shah</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2"> Consultant - Nanavati Institute of Spine Surgery</div>
         </v-card-text>
    </v-card>
  </v-hover>
<!--Mihir-->
  <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Mihir.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr. Mihir Bapat</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2"> Director & Sr Consultant - Nanavati Institute of Spine Surgery</div>
         </v-card-text>
    </v-card>
  </v-hover>
</v-row>
<!--3rd row-->
<!--Nikhil-->

<v-row justify="center">

<v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Nikhil.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr. Nikhil Arbatti</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2">Senior Consultant - Minimally Invasive & Endoscopic Spine Surgery</div>
         </v-card-text>
    </v-card>
  </v-hover>
  <!--ANil-->

  <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Anil.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr. Anik Venkitachilam</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2"> Consultant - (Neurology) and Movement Disorders</div>
         </v-card-text>
    </v-card>
  </v-hover>
<!--Harshadbhai-->
  <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Harshad.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr. Harshadrai Parekh</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2">Surgeon-Neurosurgery</div>
         </v-card-text>
    </v-card>
  </v-hover>
<!--Sunanda-->
  <v-hover v-slot:default="{ hover }">
    <v-card
       class="mx-0 pa-0 ml-0"
      width="300"
      color="white"
    >
      <v-img
        :aspect-ratio="12/14"
        src="Sunanda.jpg"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out grey lighten-5 v-card--reveal display-0 white--text"
            style="height: 100%;"
          > <overline>
          <strong class="pink--text text--darken-4 ">
             Education:
         <li>MBBS</li>
        <li> MD</li> 
        <li> DM</li>
         <li>FINR</li>
         <br> </br>
         Experience
         <li>18 Years of Work Experience</li>
         </strong>
          </overline>
          </div> 
        </v-expand-transition>
        
      </v-img>
      <v-card-text
        class="pt-4"
        style="position: relative;"
      >
      <!--button is commented
        <v-btn
          absolute
          color="orange"
          class="white--text"
          fab
          large
          right
          top
        >
          <v-icon>mdi-cart</v-icon>
        </v-btn>-->
       
        <h3>
         <strong class="pink--text text--darken-4" ><h2>Dr.Sunanda Anand</h2> </strong>
         <!--<div class="font-weight-pink--text">Dr. Pradyuman Oak</div> -->
         </h3>
         <div class="font-weight-light grey--text title mb-2">Consultant - Neurology & Interventional Neuroradiology</div>
         </v-card-text>
    </v-card>
  </v-hover>

</v-row>


        
 
  </v-row>
  </v-container>
</template>

