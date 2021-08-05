<template>
  <v-app>
    <v-app-bar
      app
      color="#042069"
      dark
    > <span class="header">


      SESKATER MERCH STORE PLES BUY MErCH
    </span>

    </v-app-bar>

    <v-main>
      <blok/>
      <line1/>
    </v-main>
  </v-app>
</template>


<script>
import blok from './components/blok';
import line1 from './components/line1';
export default {
  name: 'App',

  components: {
  blok, line1
  },

  data: () => ({
    //
  }),
};
</script>
<style >
.header
{
  font-size: 20px;
  font-weight: bolder;
  color: antiquewhite;
}
</style>
