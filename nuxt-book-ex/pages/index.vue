<template>
  <v-app id="index-page">
    <section>
      <v-parallax src="https://github.com/vwxyzjn/vuetify-parallax-starter2/raw/master/src/assets/background1.jpg" height="450">
        <v-layout column align-center justify-center>
          <h2 class="teal--text text--lighten-2 mb-2">Parallax Template</h2>
          <div class="white--text headline mb-3 text-xs-center">A modern responsive front-end framework based on Material Design</div>
          <v-btn light large class="teal lighten-2 white--text" href="https://github.com/vwxyzjn/vuetify-parallax-starter">Get Started</v-btn>
        </v-layout>
      </v-parallax>
    </section>
    <div id="content">
      <v-layout row wrap class="my-5" >
        <v-flex xs12 sm4>
          <v-card class="elevation-0">
            <v-card-media height="45px" class="text-xs-center">
              <v-icon x-large class="brown--text">flash_on</v-icon>
            </v-card-media>
            <v-card-title primary-title>
              <div class="headline text-xs-center" style="width:100%">Speeds up development</div>
            </v-card-title>
            <v-card-text>
              We did most of the heavy lifting for you to provide
              a default stylings that incorporate our custom components.
              Additionally, we refined animations and transitions to
              provide a smoother experience for developers.
            </v-card-text>
          </v-card>
        </v-flex>

        <v-flex xs12 sm4>
          <v-card class="elevation-0">
            <v-card-media height="45px" class="text-xs-center">
              <v-icon x-large class="brown--text">group</v-icon>
            </v-card-media>
            <v-card-title primary-title>
              <div class="headline text-xs-center" style="width:100%">User Experience Focused</div>
            </v-card-title>
            <v-card-text>
              By utilizing elements and principles of Material Design,
              we were able to create a framework that incorporates components
              and animations that provide more feedback to users. Additionally,
              a single underlying responsive system across all platforms allow
              for a more unified user experience.
            </v-card-text>
          </v-card>
        </v-flex>

        <v-flex xs12 sm4>
          <v-card class="elevation-0">
            <v-card-media height="45px" class="text-xs-center">
              <v-icon x-large class="brown--text">settings</v-icon>
            </v-card-media>
            <v-card-title primary-title>
              <div class="headline text-xs-center" style="width:100%">Easy to work with</div>
            </v-card-title>
            <v-card-text>
              We have provided detailed documentation as well as specific code
              examples to help new users get started. We are also always open
              to feedback and can answer any questions a user may have about
              Materialize.
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
    </div>
    </section>

    <section>
      <v-parallax src="https://github.com/vwxyzjn/vuetify-parallax-starter2/raw/master/src/assets/background2.jpg" height="380">
        <v-layout column align-center justify-center>
          <div class="headline white--text text-xs-center">A modern responsive front-end framework based on Material Design</div>
        </v-layout>
      </v-parallax>
    </section>

    <section>
      <div id="content">
        <v-layout row wrap class="my-5" >
          <v-flex xs12>
            <v-card class="elevation-0">
              <v-card-title primary-title>
                <div class="headline text-xs-center" style="width:100%">Contact Us</div>
              </v-card-title>
              <v-card-text>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam scelerisque id nunc nec volutpat.
                Etiam pellentesque tristique arcu, non consequat magna fermentum ac. Cras ut ultricies eros.
                Maecenas eros justo, ullamcorper a sapien id, viverra ultrices eros. Morbi sem neque, posuere
                et pretium eget, bibendum sollicitudin lacus. Aliquam eleifend sollicitudin diam, eu mattis nisl
                maximus sed. Nulla imperdiet semper molestie. Morbi massa odio, condimentum sed ipsum ac, gravida
                ultrices erat. Nullam eget dignissim mauris, non tristique erat. Vestibulum ante ipsum primis in
                faucibus orci luctus et ultrices posuere cubilia Curae;
              </v-card-text>
            </v-card>
          </v-flex>
        </v-layout>
      </div>
    </section>
    <v-content>
      <v-container>

      </v-container>
    </v-content>
  </v-app>
</template>

<script>
  export default {
    components: {}
  }
</script>
<style>
</style>
