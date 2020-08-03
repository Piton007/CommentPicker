<template>
  <v-container class="justify-center d-flex" fluid >
      <v-card  >
          <v-img :src="img"></v-img>
          <v-card-title >
              <a class="text-decoration-none home_url" :href="home_url" target="_blank"> {{username}}</a>
          </v-card-title>
      </v-card>
  </v-container>
</template>

<script>
export default {
    data:()=>({
        username:"Jose Luis Morales Watanabe",
        "home_url":"https://www.facebook.com/joseluis191913",
        img:"https://i.pinimg.com/originals/f8/18/6b/f8186b8f1b13ddb159119147d6430831.jpg"
    })
}
</script>

<style scoped>
    .img {
        width: 80px;
        height: 80px;
    }
</style>