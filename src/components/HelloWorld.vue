<template>
  <v-container>
    <v-row>
      <v-col lg="5" md="5" sm="12">
        <div class="h purple center">
          <v-btn
            :loading="loading3"
            :disabled="loading3"
            color="blue-grey"
            class="ma-2 white--text"
            @click="loader = 'loading3'"
          >
            Upload
            <v-icon right dark> mdi-cloud-upload </v-icon>
          </v-btn>
        </div>
      </v-col>
      <v-col>
        <div class="center mg">
          <v-btn>Convert 🔁</v-btn>
        </div>
      </v-col>
      <v-col lg="5" md="5" sm="12">
        <div class="h green"></div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<style scoped>
body{
  overflow: hidden;
}
.h {
  height: 500px;
}
.center {
  display: flex;
  justify-content: center;
  align-items: center;
}
.mg {
  margin: auto auto;
  width: fit-content;
}
</style>
