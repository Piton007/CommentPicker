<template>
  <v-container>
      <v-row>
          <v-col cols=12>
              <v-text-field  v-model="post_url" label="Post Url" outlined :placeholder="default_link" >
                  <template v-slot:prepend>
                    <v-icon color="primary">fa-link</v-icon>
                      
                  </template>
              </v-text-field>
          </v-col>
      </v-row>
  </v-container>
</template>

<script>

export default {
    data:()=>({
        post_url:"",
        default_link:"e.g https://www.facebook.com/FuenteCodigo/posts/122003041233"
    })
}
</script>

<style>

</style>