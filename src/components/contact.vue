<template>
  <v-container>
    <v-row>
      <v-col cols="12" md="6">
        <v-card class="pa-3 color__green" style="margin-top: 20px;">
          <h3 class="mb-2">Email</h3>
          <p>{{ email }}</p>
        </v-card>
      </v-col>
      <v-col cols="12" md="6">
        <v-card class="pa-3 color__green" style="margin-top: 20px;">
          <h3 class="mb-2">Phone</h3>
          <p>{{ phone }}</p>
        </v-card>
      </v-col>
      <v-col cols="12" md="6">
        <v-card class="pa-3 color__green" style="margin-top: 20px;">
          <h3 class="mb-2">Facebook</h3>
          <p>{{ facebook }}</p>
        </v-card>
      </v-col>
      <v-col cols="12" md="6">
        <v-card class="pa-3 color__green" style="margin-top: 20px;">
          <h3 class="mb-2">Address</h3>
          <p>{{ address }}</p>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      email: 'haritbd47@gmail.com',
      phone: '(+66) 95-701-3997',
      facebook: 'Harit Benjang',
      address: '35/13 The sweet garden Village, Bangkok 10510',
    };
  },
};
</script>

<style scoped>
.color__green {
  background-color: green;
  color: white;
}
</style>