<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <Navbar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="FORMALPIC.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h3 class="black--text top">Hello, I am Jannatun Naym</h3>
          <h1 class="red--text">Software Engineer</h1>
          <p class="black--text">
            Desirous of a position in a dynamic workplace <br />
            that encourages new ideas and provides opportunities for
            advancement,<br />
            as well as a good work atmosphere in which I can demonstrate my<br />
            abilities by working hard and achieving organizational goals.
          </p>
          <v-btn tile color="#A7121D" dark>about me</v-btn>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3">
                    mdi-palette-swatch
                  </v-icon>
                  <h3 class="white--text ml-3 mt-4">
                    Collaborative Filtering Based<br />
                    Recommendation system(Thesis)
                  </h3>
                  <p class="grey--text ml-3 mt-6">
                    An user based recommendation system <br />
                    based on previoussearch with a conference website.
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right> mdi-arrow-right </v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon color="#A7121D" x-large class="ml-3" dark>
                    mdi-shopping
                  </v-icon>
                  <h3 class="white--text ml-3 mt-4">
                    Online news portal<br /><br />
                  </h3>
                  <p class="grey--text ml-3 mt-6">
                    Shows various kinds of news dynamically <br /><br />
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right> mdi-arrow-right </v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3" dark>
                    mdi-book-open-page-variant
                  </v-icon>
                  <h3 class="white--text ml-3 mt-4">
                    Server-client web server<br /><br />
                  </h3>
                  <p class="grey--text ml-3 mt-6">
                    Manipulates requests from clients<br />
                    using multithread
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right> mdi-arrow-right </v-icon>
                  </v-btn>
                </div>
              </v-col>
              <v-col cols="12" class="mt-10">
                <div class="child1">
                  <h1 class="red--text text-darken-4 mt-4 number">6</h1>
                  <h3 class="black--text mt-4">Months Android Training</h3>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="red--text text--darken-4">React JS</h1>
                        <p class="grey--text">Redux,Hook</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text--darken-4">Javascript</h1>
                        <p class="grey--text">Basic, Dom manupulation</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="red--text text--darken-4">PHP</h1>
                        <p class="grey--text">Basic Knowledge</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text--darken-4">MySql</h1>
                        <p class="grey--text">CRUD Operation</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>

        <br />
        <br />
        <v-col md="3" offset-md="3" id="about">
          <h1 class="#11111150">Education</h1>
        </v-col>
        <v-col md="3" class="text-end">
          <v-btn tile color="#A71210" dark>View All</v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="280px"
            color="#eceff1"
            elevation="3"
          >
            <v-img src="Ewu.png" contain> </v-img>
            <br />
            <h3 class="red--text">Completed Bsc from EWU</h3>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card
            class="pa-2 py-12"
            outlined
            tile
            height="280px"
            color="#eceff1"
            elevation="3"
          >
            <v-img src="download.jpg" contain> </v-img>
            <br />
            <br />

            <h3 class="red--text">
              Completed HSC and SSC from <br />
              Motijheel Model School and College
            </h3>
          </v-card>
        </v-col>

        <v-col cols="12" class="padd topInverse">
          <div class="secondchild1" id="contact">
            <v-row>
              <v-col cols="7">
                <h1 class="white--text">
                  Lets Work Together for a better future
                </h1>
                <p class="white--text">
                  Janatun Naym Moon<br />
                  jannatunnaym0909@gmail.com<br />
                  01854808304
                </p>
              </v-col>
            </v-row>
          </div>

          <!-- <v-toolbar class="topTolbar" dark color="#ffffff" flat>
            <div
              style="
                position: absolute;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
            >
              <v-btn text>Home</v-btn>
              <v-btn text>Project</v-btn>
              <v-btn text>About</v-btn>
              <v-btn text>Contect</v-btn>
            </div>
          </v-toolbar> -->
        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import Navbar from "@/components/Nav-bar.vue";
import Footer from "../components/Footer-var.vue";

export default {
  name: "Home-view",

  components: {
    Navbar,
    Footer,
  },
};
</script>
<style scoped>
.top {
  margin-top: 180px;
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
  background: "white";
  /* background: linear-gradient(
    to right,
    #0ba6ed,
    #0ba6ed 50%,
    #03a9f4 50%,
    #03a9f4 50%
  ); */
  text-align: center;
  padding: 2rem 2rem;
}

.second {
  widows: 100%;
  height: 400px;
  background: #72b6c0;
  text-align: center;
  padding: 2rem 2rem;
}

.secondchild1 {
  display: inline-block;
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
  background-color: #5739d0;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
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
  padding: 8px 0px;
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
</style>
