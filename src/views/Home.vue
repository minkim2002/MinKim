<template>
  <v-app id="Home" :style="{ background: $vuetify.theme.themes.dark.background }">
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="2">
        </v-col>
        <v-col cols="3">
          <v-carousel cycle height="auto">
            <v-carousel-item src="21.jpg" cover></v-carousel-item>
            <v-carousel-item src="19.jpg" cover></v-carousel-item>
            <v-carousel-item src="20.jpg" cover></v-carousel-item>
            <v-carousel-item src="17.jpg" cover></v-carousel-item>
            <v-carousel-item src="22.jpg" cover></v-carousel-item>
          </v-carousel>
        </v-col>
        <v-col cols="1">
        </v-col>
        <v-col cols="6">
          <h5 id="occupation" class="text--darken-4 top">Software Engineer</h5>
          <h1 class="white--text">Hi, I'm Min</h1>
          <p class="grey--text">
            An undergraduate student majoring in
            <br />
            Computer Science and Economics at William & Mary.
            <br />
            Based on thoroughly equipped front and back-end programming skills,
            <br />
            ambitious with personal/team growth and success through higher education, <br /> research, and internship
            opportunities.
          </p>
          <AboutMePopUp />
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="Introduction">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#958b00" x-large class="ml-3">mdi-file-code</v-icon>
                  <h3 class="white--text ml-3 mt-4">Software Engineering</h3>
                  <p class="grey--text ml-3 mt-6">
                    Check My Coding Work!
                  </p>
                  <v-btn color="#958b00" dark text href="https://github.com/minkim2002">
                    GitHub
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon color="" x-large class="ml-3" dark>mdi-security</v-icon>
                  <h3 class="white--text ml-3 mt-4">Cybersecurity</h3>
                  <p class="grey--text ml-3 mt-6">
                    Check My Research Paper!
                  </p>
                  <v-btn color="" dark text
                    href="https://digitalcommons.odu.edu/covacci-undergraduateresearch/2023spring/projects/2/">
                    Research
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>

                <div class="child bgColor1">
                  <v-icon color="#958b00" x-large class="ml-3">mdi-lightbulb</v-icon>
                  <h3 class="white--text ml-3 mt-4">Product Management</h3>
                  <p class="grey--text ml-3 mt-6">
                    Check My Resume!
                  </p>
                  <v-btn color="#958b00" dark text href="https://www.linkedin.com/in/min-kim1103/">
                    LinkedIn
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <v-img src="wm.png"></v-img>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="text--darken-4 category">CS & ECON</h1>
                        <p class="grey--text">Majors</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 id="scholar" class="text--darken-4 category">Archibald-Finifter
                        </h1>
                        <p class="grey--text">Scholarship</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="text--darken-4 category">3.85</h1>
                        <p class="grey--text">GPA</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="text--darken-4 category">06.2024</h1>
                        <p class="grey--text">Graduation</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="6" offset-md="3" id="About">
          <h4 class="white--text">About</h4>
          <p class="grey--text">Know more about me!</p>
        </v-col>
        <!-- <v-col md="3" class="text-end">
          <v-btn tile color="#958b00" dark> View All (Working)</v-btn>
        </v-col> -->
        <v-col md="3" offset-md="3">
          <v-card class="pa-2 py-6" outlined tile height="250px" color="#1E1E1E">
            <v-img src="5.jpg" contain max-height="500"></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card class="pa-2 py-3" outlined tile height="250px" color="#1E1E1E">
            <v-img src="2.jpg" contain max-height="500"></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> Gallery </v-btn><br />

          <GalleryPopUp />
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> Interests </v-btn><br />

          <InterestsPopUp />
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card class="pa-2 py-4" outlined tile height="250px" color="#1E1E1E">
            <v-img src="7.png" contain max-height="500"></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card class="pa-2 py-3" outlined tile height="250px" color="#1E1E1E">
            <v-img src="8.png" contain max-height="500"></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn color="white" dark text class="ml-n4"> Programming Languages </v-btn><br />

          <ProLangPopUp />
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> Other Technologies </v-btn><br />
          <OtherTechPopUp />
        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="Contact">
              <v-row>
                <v-col cols="12">
                  <h2 class="white--text">
                    Contact me if you have any questions!
                  </h2>
                </v-col>
                <v-col cols="12">
                  <v-btn tile color="#958b00" dark class="mt-16" href="mailto: minkimdom1103@gmail.com">
                    Contact
                  </v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div style="
                position: absolute;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              ">
              <v-btn text @click="scroll('Home')">Home</v-btn>
              <v-btn text @click="scroll('Introduction')">Introduction</v-btn>
              <v-btn text @click="scroll('About')">About</v-btn>
              <v-btn text @click="scroll('Contact')">Contact</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";
import AboutMePopUp from "../components/AboutMePopUp.vue"
import OtherTechPopUp from "../components/OtherTechPopUp.vue";
import ProLangPopUp from "../components/ProLangPopUp.vue";
import GalleryPopUp from "../components/GalleryPopUp.vue"
import InterestsPopUp from "../components/InterestsPopUp.vue"

export default {
  name: "Home",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Footer,
    AboutMePopUp,
    OtherTechPopUp,
    ProLangPopUp,
    GalleryPopUp,
    InterestsPopUp
  },

  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>
<style scoped>
.top {
  margin-top: 100px;
}

.topInverse {
  margin-top: -250px;
}

.topTolbar {
  margin-top: 100px;
  text-align: center;
}

.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(to right,
      #181818,
      #181818 50%,
      #111111 50%,
      #111111 50%);
  text-align: center;
  padding: 2rem 2rem;
}

.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}

.secondchild1 {
  display: inline-block;
  width: 650px;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}

.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}

.bgColor1 {
  background-color: #1e1e1e;
}

.bgColor2 {
  background-color: #958b00;
}

.child1 {
  display: inline-block;
  padding: 0.5rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}

.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}

.mRight {
  margin-right: 8px;
}

.mButton {
  margin-bottom: 8px;
}

.padding {
  padding: 8px 0;
}

.col-12.padd {
  padding: 12px 0 !important;
}

.col-12.childcol {
  padding: 0 !important;
}

h1.number {
  font-size: 50px;
  font-weight: bold;
}

.category {
  font-size: 28px;
  color: #958b00;
}

#occupation {
  color: #958b00
}
</style>