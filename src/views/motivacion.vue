 <template>
<div >
<v-app class="color cyan">
<div >
 <v-app-bar  class="color cyan">
      <v-btn 
   href="/info"
      
        text
      >
        <span class="mr-2"></span>
         <v-icon color black >mdi-arrow-left</v-icon>
      </v-btn>
      <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://i.ibb.co/kgfsCJx/panda-logo-final.png"
          transition="scale-transition"
          width="70"
          height="50"
        />
  
<v-toolbar-title class="white--text">KODIA</v-toolbar-title> 


<v-spacer></v-spacer><v-spacer></v-spacer>
<v-btn class="ma-2 ,white--text" outlined color="white" href="/info">LOGUEARSE</v-btn>
 </v-app-bar >
 </div  >
 <h1  justify="center" 
      align="center" class="white--text">MOTIVACIÓN</h1>
            

 <v-container fluid class=" color cyan"  >
 
 <v-row wrap>
          
 
<v-col  
            justify="center" 
            align="center"  
            class="color cyan"
             cols="6"  >
                
<v-img src="https://i.ibb.co/82cc6BT/motivacionfoto.png"
 aspect-ratio="1.1"
 max-width="400"
 max-height="300"></v-img>

</v-col>
  

 <v-col  
            justify="center"
             align="center" 
              class="color #00B9D8"
               cols="6"  
               
               >
                  

    <v-img src=" https://i.ibb.co/BZgvS0Y/letras-ia.png"
 aspect-ratio="0.999"
 max-width="450"
 max-height="700"></v-img>

            </v-col>
             
        </v-row>
     
    </v-container>
</v-app>

 </div>
 

</template>