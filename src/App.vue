<template>
  <v-app>
    <v-main >
      <router-view v-slot="{ Component }">
        <transition name="fade" mode="out-in">
          <component :is="Component" />
        </transition>
      </router-view>
    </v-main>
    <v-bottom-navigation app dark>
      <v-layout>
        <v-row>
          <v-col class="d-flex align-center">
            <router-link to="/">
              <h1 style="color: white; margin-left: 10px">
                iftech
              </h1></router-link
            ></v-col
          >

          <v-col class="d-flex align-center justify-center">
            <v-btn style="margin-left: 10px" to="/about">About</v-btn>

            <v-btn style="margin-left: 10px" to="/contact">Contact</v-btn>
          </v-col>

          <v-col></v-col>
        </v-row>
      </v-layout>
    </v-bottom-navigation>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({}),
};
</script>

<style lang="scss">
html,body {
  margin: 0;
  overflow: hidden;
}
</style>