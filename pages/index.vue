<template>
  <v-container grid-list-md text-xs-center>
    <v-layout row wrap>
      <v-flex xs12>


        <div class="row-wrapper">
          <div class="row-spacer">
            <div class="row-box">
              <div class="image-container image-1"></div>
            </div>
            <div class="row-box2">
              <div style="row-box-text">
                <h1>Johanna och Patrik</h1>
                <span class="date">2019-08-03</span>
              </div>
            </div>
          </div>
        </div>


        <div class="block-1" style="">
          <div class="block-2" style="">
            <div class="block-3" style="">
              <div class="block-4" style="">
                <div class="block-5" style="">
	                <h2>Vigsel</h2> 
                </div>
                <p>Vigseln äger rum i Munsö kyrka kl 14.30. <br>
                Barn är välkomna i kyrkan men där efter vill vi fira med våra vuxna gäster. <br><br>
                Till kyrkan tar man sig <br>
                1: egen maskin <br>
                2: buss nr.. från bromma,<br>
                3: taxi/uber (karta och adress: Slutvägen 3, 178 91 Munsö). <br><br>
                Vigseln pågår i ungefär en timme och därefter kommer gästerna att transporteras till landstället på ön malmhuvud där festen fortsätter!</p>
              </div>
              
          </div>
          <div class="block-6" style="">
            <div class="image-container image-2" style="">
          </div>
        </div>
      </div>
    </div>







        <!-- <v-card color="primary">
          <v-card-text class="px-0">
            
        
            <h2>Vigsel</h2> 
            <p>Vigseln äger rum i Munsö kyrka kl 14.30. Barn är välkomna i kyrkan men där efter vill vi fira med våra vuxna gäster. Till kyrkan tar man sig 1: egen maskin 2: buss nr.. från bromma, 3: taxi/uber (karta och adress: Slutvägen 3, 178 91 Munsö). Vigseln pågår i ungefär en timme och därefter kommer gästerna att transporteras till landstället på ön malmhuvud där festen fortsätter!</p>
      
            <h2>Klädsel</h2>
            <p>Du kan bära kostym eller en sommarfin blåsa, ha skor som du gillar men som samtidigt är funktionella. Vi kommer att tillbringa kvällen utomhus så medtag ett varmare plagg. </p>
      
            <h2>Mat</h2>
            <p>Vi bjuder på tilltugg och cava vid ankomst på malmhuvud, därefter en sommarbuffé, bröllopstårta och öppen bar. Meddela oss om allergier vi behöver ta hänsyn till på XXX@XXX</p>
      
            <h2>Hemgång</h2>
            <p>Det kommer finnas två tidpunkter då du kan transporteras från ön varav den sista tiden också inkluderar en busstransport till Bromma och sedan Järfälla. Dessa tidpunkter är 23.00 och 02.00.</p>
      
            <h2>Presenter</h2>
            <p>Er närvaro är allt vi önskar! Vill ni dock uppmärksamma vår dag ytterligare önskar vi oss ett bidrag till smekmånaden alternativt till välgörande ändamål: Till: XXX OSA senast 3/5.</p>

            <h2>Toastmasters</h2>
          </v-card-text>
        </v-card> -->
      </v-flex>
        

    </v-layout>
  </v-container>
</template>

<script>
import Vue from 'vue'
import Vuetify from 'vuetify'
import 'vuetify/dist/vuetify.min.css'

Vue.use(Vuetify)



export default {
  components: {

  }
}
</script>

<style>

 @import url('https://fonts.googleapis.com/css?family=Kaushan+Script|PT+Sans');

.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.row-wrapper{
  float:none;
  width:100%;
  padding-top:0%;
  padding-left:0px;
  padding-right:0px;
  padding-bottom:0%;
  margin-top:0%;
  margin-bottom:0em;
  text-align:center;
  color:#17140f;
  max-width:1200px;
  display:inline-block
}
.row-spacer{
  padding-top:5%;
  padding-right:0em;
  padding-bottom:5%;
  padding-left:0em
}
.row-box{
  float:right;
  display:inline-block;
  width:54%;
  padding-top:0%;
  padding-left:0%;
  padding-right:0%;
  padding-bottom:0%;
  background-color:rgb(50, 56, 99);
  margin-top:16%;
  margin-left:-4%;
  margin-right:0%;
  margin-bottom:0px;
  -webkit-transform:translateX(0%);
  -moz-transform:translateX(0%);
  -ms-transform:translateX(0%);
  transform:translateX(0%);
  -ms-transform:translateX(0%);
  -webkit-transform:translateX(0%)
}
.row-box2{
  float:left;
  display:inline-block;
  width:54%;
  padding:1em;
  padding-top:12%;
  padding-left:6%;
  padding-right:6%;
  padding-bottom:12%;
  background-color:#754d34;
  margin-top:0px;
  margin-left:0%;
  margin-right:-4%;
  margin-bottom:0px;
  position: relative;
}
.image-container{
  padding-top:0em;
  padding-left:0em;
  padding-right:0em;
  background-size:cover;
  background-position:center center;
  background-repeat:no-repeat;
  background-attachment:0em;
}
.image-1{
  padding-bottom:70%;
  background-image:url('/patrik-johanna-water.jpg')
}
.image-2{
  padding-bottom:100%;
  background-image:url('/kyrka.jpg')
}
.row-box-text{
  margin-bottom:5%;
  float:none;
  display:inline-block;  
  padding-top:0em;
  padding-right:0em;
  padding-bottom:0em;
  padding-left:0em;
  line-height:100%;
  text-transform:uppercase;
  letter-spacing:10px;
  text-align:left
}

h1,h2,h3,.date{
  font-family: 'Kaushan Script', cursive;
}
h1{
  font-size: 52px;
}
h2{
  font-size: 42px;
}
.date{
  font-size: 32px;
}

.block-1{
  float:none;
  width:100%;
  padding:1em;
  padding-top:0%;
  padding-left:0px;
  padding-right:0px;
  padding-bottom:0%;
  margin-top:0%;
  margin-bottom:0em;
  text-align:center;
  color:#ffffff;
  display:inline-block
}
.block-2{
  padding-top:5%;
  padding-right:0em;
  padding-bottom:5%;
  padding-left:0em
}
.block-3{
  float:right;
  display:inline-block;
  width:54%;
  padding:1em;
  padding-top:10%;
  padding-left:10%;
  padding-right:10%;
  padding-bottom:10%;
  background-color:rgb(50, 56, 99);
  margin-top:0px;
  margin-left:-4%;
  margin-right:0px;
  margin-bottom:0px
}
.block-4{
  padding:1em;
  width:100%;
  padding-top:0em;
  padding-left:0em;
  padding-right:0em;
  padding-bottom:0em
}
.block-5{
  margin-bottom: 5%; 
  float: none; 
  display: inline-block;  
  padding: 0em; 
  line-height: 100%; 
  min-height: 32px;
}
.block-6{
  float:left;
  display:inline-block;
  width:50%;
  padding-top:0%;
  padding-left:0%;
  padding-right:0%;
  padding-bottom:0%;
  background-color:rgb(50, 56, 99);
  margin-top:6%;
  margin-left:3%;
  margin-right:-4%;
  margin-bottom:0px;
  -webkit-transform:translateX(0%);
  -moz-transform:translateX(0%);
  -ms-transform:translateX(0%);
  transform:translateX(0%);
  -ms-transform:translateX(0%);
  -webkit-transform:translateX(0%)
}
</style>

