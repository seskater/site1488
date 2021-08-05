<template>
<div class="blok-wrap">
  <v-container>
    <div class="text-center-wrap">
      <div class="text-center">
        <h1 class="welkam">
          WELKAM
        </h1>
      </div>
      <div class="text-center">
        <p class="textet">
          ples buy merch
        </p>
      </div>
      <div class="text-center">
        <v-btn  color="#420f69"
          depressed
          elevation="24"
          x-large
          dark
          rounded


        >
          bue
        </v-btn>
      </div>
    </div>


  </v-container>
</div>
</template>

<script>
  export default {
    name: 'blok',

    data: () => ({

    }),
  }
</script>

<style scoped>
.blok-wrap {
  background-color: #696969;
   height: 100%
}
.text-center-wrap {
  margin-top: 150px;
}
.text-center {
  color:blanchedalmond;
  display: flex;
  justify-content: center;
  align-items: center;
}
.welkam {
  font-size: 47px;
  font: bold;

}
.textet {


}

</style>
