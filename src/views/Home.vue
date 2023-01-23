<template>
  <v-app id="Home" :style="{ background: $vuetify.theme.themes.dark.background }">
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="profile.png" position="bottom" contain max-height="400"></v-img>
        </v-col>
        <v-col cols="6">
          <h5 id="occupation" class="text--darken-4 top">Software Engineer</h5>
          <h1 class="white--text">Hi, I'm Min</h1>
          <p class="grey--text">
            A passionate undergraduate student majoring in
            <br />
            Computer Science and Economics at William & Mary.
            <br />
            Based on thoroughly equipped front and back-end programming skills,
            <br />
            ambitious with personal/team growth and success through higher education, research, and internship
            opportunities.
          </p>
          <v-btn tile color="#958b00" dark> about me (Working) </v-btn>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="Summary">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#958b00" x-large class="ml-3">mdi-file-code</v-icon>
                  <h3 class="white--text ml-3 mt-4">Software Engineering</h3>
                  <p class="grey--text ml-3 mt-6">
                    Check my work at <br /><a href="https://github.com/minkim2002">my github!</a>

                  </p>
                  <v-btn color="#958b00" dark text>
                    know more (working)
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon color="" x-large class="ml-3" dark>mdi-security</v-icon>
                  <h3 class="white--text ml-3 mt-4">Cybersecurity</h3>
                  <p class="grey--text ml-3 mt-6">
                    Check my resume at <br /><a href="https://www.linkedin.com/in/min-kim1103/">my linkedin!</a>
                  </p>
                  <v-btn color="" dark text>
                    know more (working)
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#958b00" x-large class="ml-3">mdi-lightbulb</v-icon>
                  <h3 class="white--text ml-3 mt-4">Product Management</h3>
                  <p class="grey--text ml-3 mt-6">
                    Check my resume at <br /><a href="https://www.linkedin.com/in/min-kim1103/">my linkedin!</a>
                  </p>
                  <v-btn color="#958b00" dark text>
                    know more (working)
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
                        <h1 class="text--darken-4 category">3.84</h1>
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
        <v-col md="3" offset-md="3" id="About">
          <h4 class="white--text">About</h4>
          <p class="grey--text">Know more about me!</p>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn tile color="#958b00" dark> View All (Working)</v-btn>
        </v-col>
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
          <v-btn color="white" dark text class="ml-n4"> Background </v-btn><br />

          <v-btn color="#958b00" dark text class="ml-n4">
            know more (working)
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> Interests </v-btn><br />

          <v-btn color="#958b00" dark text class="ml-n4">
            know more (working)
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
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
          <v-btn color="white" dark text class="ml-n4"> Programming Language </v-btn><br />

          <v-btn color="#958b00" dark text class="ml-n4">
            know more (working)
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn color="white" dark text class="ml-n4"> Coming Up.... </v-btn><br />
          <v-btn color="#958b00" dark text class="ml-n4">
            know more (working)
            <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="Contact">
              <v-row>
                <v-col cols="8">
                  <h1 class="white--text">
                    Contact me if<br />you have any questions!
                  </h1>
                  <p class="grey--text">
                    personal email: <a href="mailto: minkimdom1103@gmail.com">minkimdom1103@gmail.com</a> <br />
                    school email: <a href="mailto: mkim22@wm.edu">mkim22@wm.edu</a> <br />
                    mobile: 703-717-8646
                  </p>
                </v-col>
                <v-col cols="4">
                  <v-btn tile color="#958b00" dark class="mt-16">
                    Contact (Working)
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
              <v-btn text>Summary</v-btn>
              <v-btn text>About</v-btn>
              <v-btn text>Contact</v-btn>
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

export default {
  name: "Home",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Footer,
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