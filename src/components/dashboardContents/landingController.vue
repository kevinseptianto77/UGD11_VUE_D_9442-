<template>
  <section
    id="welcome"
    class="hide-overflow"
  >
    <v-layout>
      <v-flex
        hidden-sm-and-down
        md6
      >
        <v-img
          src="https://cdn.vox-cdn.com/thumbor/y_zQVlSf3T9JXNsdTVZ-V1lDZCc=/0x227:1688x1688/1200x675/filters:focal(731x663:1001x933)/cdn.vox-cdn.com/uploads/chorus_image/image/60222205/InfinityWar5aabd55fed5fa.0.jpg"
          height="100vh"
        />
      </v-flex>

      <v-flex
        xs12
        md6
        align-content-space-between
        layout
        :pa-5="$vuetify.breakpoint.smAndDown"
        wrap
      >
        <base-bubble-1
          style="transform: rotate(180deg) translateY(25%)"
        />

        <v-layout
          align-center
          justify-center
        >
          <v-flex
            xs10
            md6
          >
            <base-heading><h1>Welcome!</h1></base-heading>
            <br>
            <base-text>
            <p style="text-align:justify">
              Welcome
              Welcome
              Welcome
              Welcome
              Welcome
              Welcome
              Welcome
              Welcome
              WelcomeWelcome
              WelcomeWelcome
              Welcome
              Welcome
              
            </p>
            </base-text>
            <base-btn class="mt-4">
                <v-btn rounded color="primary" dark router to="/user">Get In</v-btn>
            </base-btn>
          </v-flex>
        </v-layout>

        <base-bubble-2
          style="transform: rotate(180deg) translate(-200px, -15%)"
        />
      </v-flex>
    </v-layout>
  </section>
</template>