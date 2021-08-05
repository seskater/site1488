<template>
<div class="line1">
  <v-row>
    <v-col  class="bb aa" cols="3">
     <div class="block-el">
       <v-icon
         color="orange"
         x-large
       >mdi-alpha-n</v-icon>
     </div>
     <div class="block-el">
       merch buy ples
     </div>
    </v-col>
    <v-col  class="gb aa" cols="3">
     <div class="block-el">
       <v-icon
         color="orange"
         x-large
       >mdi-alpha-i</v-icon>
     </div>
     <div class="block-el"> merch buy ples</div>
    </v-col>
    <v-col  class="bb aa" cols="1">
    <div class="block-el">
      <v-icon
        color="orange"
        x-large
      >mdi-alpha-g</v-icon>
    </div>

    </v-col>
    <v-col  class="bb aa" cols="2">
     <div class="block-el">
       <v-icon
         color="orange"
         x-large
       >mdi-alpha-g mdi-alpha-g</v-icon>
     </div>
      <div class="block-el"> merch buy ples</div>
    </v-col>
    <v-col  class="gb aa" cols="3">
      <div class="block-el">
        <v-icon
          color="orange"
          x-large
        >mdi-alpha-a</v-icon>
      </div>
     <div class="block-el"> merch buy ples</div>
    </v-col>
  </v-row>
</div>
</template>

<script>
  export default {
    name: 'line1',

    data: () => ({
    }),
  }
</script>
<style scoped>
.bb {
  background-color: #420f69;
}
.gb {
  background-color: #042069;
}
  .aa {
    font-weight: revert;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .block-el {
    display: flex;
    justify-content: center;
  }


</style>
