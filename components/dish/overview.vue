<script>
export default {
  data() {
    return {
      rating: 4
    }
  }
}
</script>
<template>
  <v-card
    class="mx-auto"
    max-width="400"
  >
    <v-img
      class="white--text align-end"
      width="100%"
      :src="require('@/assets/images/dishes/wildreis.jpg')"
    >
      <div class="title-class">
        <h3 class="ml-2">Ofengemüse mit Wildreis</h3>
        <v-rating
          v-model="rating"
          class="ml-2"
          small
          color="yellow darken-3"
          background-color="grey darken-1"
          empty-icon="$ratingFull"
          half-increments
          hover
        ></v-rating>
      </div>
    </v-img>

<!--    <v-card-subtitle class="pb-0">-->
<!--      Number 10-->
<!--    </v-card-subtitle>-->

<!--    <v-card-text class="text&#45;&#45;primary">-->
<!--      <div>Whitehaven Beach</div>-->

<!--      <div>Whitsunday Island, Whitsunday Islands</div>-->
<!--    </v-card-text>-->

<!--    <v-card-actions>-->
<!--      <v-btn-->
<!--        color="orange"-->
<!--        text-->
<!--      >-->
<!--        Share-->
<!--      </v-btn>-->

<!--      <v-btn-->
<!--        color="orange"-->
<!--        text-->
<!--      >-->
<!--        Explore-->
<!--      </v-btn>-->
<!--    </v-card-actions>-->
  </v-card>
</template>
<style scoped>
.title-class {
  background-color: #afafaf;
  opacity: 90%;
}
</style>
