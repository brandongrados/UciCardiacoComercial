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

<v-spacer></v-spacer>
<v-btn class="ma-2 ,white--text" outlined color="white" href="/info">LOGUEARSE</v-btn>

 </v-app-bar >
 </div  >
 <h1  justify="center" 
            align="center" class="white--text">REPORTES</h1>
 <v-container fluid class=" color cyan"  >
  
 <v-row wrap>
          

  <v-col  
            justify="center" 
            align="center"  
            class="color #00B9D8"
             cols="12"  >
                
 <h2    class="white--text">                                                                                                      

 </h2>
            <v-img src="https://i.ibb.co/sHD04zV/letras-reporte.png"
 aspect-ratio="1.1"
 max-width="1200"
        max-height="250"></v-img>

  </v-col>
          </v-row>
            
<v-row>
<v-col cols="6"   justify="center" 
            align="center"  >
<v-img src="https://i.ibb.co/sRxrTx7/reporte01.png"
 aspect-ratio="1.6"
 max-width="400"
        max-height="500"></v-img>
</v-col>
<v-col cols="6"   justify="center" 
            align="center"  >
<v-img src="https://i.ibb.co/4spH4zg/reportes02.png"
 aspect-ratio="1.8"
 max-width="400"
        max-height="400"></v-img>

</v-col>



</v-row>
            
             
      
     
    </v-container>
</v-app>

 </div>
 

</template>


