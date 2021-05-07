<template>
  <div class="home" >
   <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- helloWorld msg="Welcome to Your Vue.js App"/> -->
    <v-img 
    dark 
    max-height="auto"
    src="https://images.pexels.com/photos/7542695/pexels-photo-7542695.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
    >
    <v-layout fill-height align-content-start >
     <v-container >
      <v-row align="center" justify="center" class="white--text">
        <v-col cols="12">
          <div class="display-2 font-weight-bold">Welcome to my page.</div>
          <div class="headline">I make videos.</div>
          <iframe id="cv" src="https://www.youtube.com/embed/ZCXogqNuel8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
          </iframe>
          <!--<iframe width="560" height="315" src="https://www.youtube.com/embed/hZ8lMWS3Ry4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
          <!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/ZCXogqNuel8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
        </v-col>
      </v-row>
     </v-container>
    </v-layout>
    </v-img>
    <v-container class="mt-5">
      <v-layout wrap>
        <v-flex xs12  id="about">
          <div class="display-1 font-weight-bold">About</div>
        </v-flex>
        <v-flex xs12 mt-3>
          <div class="body-1">{{aboutText}}</div>
        </v-flex>
      </v-layout>
      <v-layout wrap mt-5>
        <v-flex xs12  id="portfolio">
          <div class="display-1 font-weight-bold">Portfolio</div>
        </v-flex>
        <!-- Kort til at placere min portfolio videoer fra YT (dobbelt tjek responsness på mobil og fuld skærm)-->
        <v-flex xs12 >
          <v-layout wrap >
            <v-flex>
                <v-flex xs12 >
                <v-card flat >
                <v-card-title >
                  <v-layout wrap > 
                    <v-flex class="d-flex-column justify-center" >
                      <!--<v-card color="blue" width="100px" height="150px"></v-card> -->
                      <iframe width="384" height="216" src="https://www.youtube.com/embed/5UIawje3Zf8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
                      </iframe>
                      <div class="title mt-2">JayR - Oh No</div>
                    </v-flex>
                     <v-flex class="d-flex-column justify-center">
                      <!--<v-card color="blue" width="100px" height="150px"></v-card> -->
                      <iframe width="384" height="216" src="https://www.youtube.com/embed/enBQJ5diIq8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
                      </iframe>
                      <div class="title mt-2">MASK - SexFactor</div>
                    </v-flex>
                  </v-layout>
                  <v-layout wrap>
                    <v-flex class="d-flex-column justify-center">
                      <!--<v-card color="blue" width="100px" height="150px"></v-card> -->
                      <iframe width="384" height="216" src="https://www.youtube.com/embed/nCXBxTWVpB8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
                      </iframe>
                      <div class="title mt-2">I$KO - Holder det 100</div>
                    </v-flex>
                     <v-flex class="d-flex-column justify-center ">
                      <!--<v-card color="blue" width="100px" height="150px"></v-card> -->
                      <iframe width="384" height="216" src="https://www.youtube.com/embed/eeR0AGeovHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
                      </iframe>
                      <div class="title mt-2">JayR - No Mercy</div>
                    </v-flex>
                  </v-layout>
                  <v-layout wrap>
                    <v-flex class="d-flex-column justify-center">
                      <!--<v-card color="blue" width="100px" height="150px"></v-card> -->
                      <iframe width="384" height="216" src="https://www.youtube.com/embed/1PbV787kTN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
                      </iframe>
                      <div class="title mt-2">NickP - Hvor Du Fra</div>

                    </v-flex>
                     <v-flex class="d-flex-column">
                      <!--<v-card color="blue" width="100px" height="150px"></v-card> -->
                      <iframe width="384" height="216" src="https://www.youtube.com/embed/mg9MGXzPqTI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
                      </iframe>
                      <div class="title mt-2">Nekhala - Overdose</div>
                    </v-flex>
                  </v-layout>
                </v-card-title>
              </v-card>
              </v-flex>

            </v-flex>
          </v-layout>
        </v-flex>

              <v-layout wrap>
                <v-flex xs12  id="contact">
                  <div class="display-1 font-weight-bold">Contact</div>
                </v-flex>
                <v-flex xs12 mt-3>
                  <div class="body-1">If you want to get in contact with me go to the link in the footer where you will find my Instagram. In there you can DM me Fosho.</div>
                </v-flex>
              </v-layout>
               
      </v-layout>
    </v-container>
     <v-footer 
                    dark
                    padless
                  >
                    <v-card
                      class="flex"
                      flat
                      tile
                      
                    >
                      <v-card-title class="black">
                        <strong class="subheading">Get connected with me on social networks!</strong>

                        <v-spacer></v-spacer>
                        <a class="link" href="https://www.instagram.com/nekhala.studio/?hl=da"> <p>instagram</p> </a>



                      </v-card-title>
                    </v-card>
                  </v-footer>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'


export default {
  name: 'Home',
  components: {
    // HelloWorld

  
  },
  data(){
    //Write about yourself downbelow Huss
    return{
      aboutText: "I'm a passionated individual that have a great experience with alot of clients. My expertise is filming and editing inside Premiere Pro and After Effect. Im know for the big Collaborations I have done With T H E  L A B and Blonde Media. Other than that I have worked with a lot of upcoming artists and right now I'm working for Selected Esbjerg, where I do all their SoMe content and managing their Instagram. You can see me as the type of guy, who likes to take all challenges and work around things with an open mindset. ",
      
    };
    
  }
};
</script>

<style >
.link{
  text-decoration: none;
}
.link p{
  color: white;

}
#cv{
width: 43.73vw;
height: 50vh;
}
@media screen and (max-width:600px) {
.home{
  width: 100vw;
}
#cv{
width: 90vw;
}}

</style>
