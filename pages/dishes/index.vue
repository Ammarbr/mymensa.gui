<template>
  <v-container>
    <v-row>
      <v-col>
        <v-text-field rounded outlined label="Search" />
      </v-col>
      <v-col class="flex-grow-0" align="right">
        <v-btn x-large color="primary">
          Add Dish
        </v-btn>
      </v-col>
    </v-row>
    <v-row>
      <v-col v-for="i in 12" cols="12" md="3">
        <DishOverview />
      </v-col>

    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
