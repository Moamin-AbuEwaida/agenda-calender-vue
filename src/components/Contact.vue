<template>
  <v-card color="white" class="rounded-lg mt-2" flat>
    <v-row>
      <v-col cols="12" sm="4">
        <v-card color="#2784ff" class="rounded-lg px-2" flat>
          <v-row>
            <v-col cols="12" sm="4">
              <v-avatar color="#dfedff" tile>
                <v-img src="p1new.png"></v-img>
              </v-avatar>
            </v-col>
            <v-col cols="12" sm="8">
              <h4 class="white--text">Irene Fleming</h4>
              <h6 class="white--text">38 years old</h6>
            </v-col>
            <v-col cols="12" sm="12" class="mt-3">
              <v-row>
                <v-col cols="12" sm="4">
                  <h6 class="grey--text text--lighten-4">Height</h6>
                  <h6 class="white--text">185</h6>
                </v-col>
                <v-col cols="12" sm="4">
                  <h6 class="grey--text text--lighten-4">Weight</h6>
                  <h6 class="white--text">80</h6>
                </v-col>
                <v-col cols="12" sm="4">
                  <h6 class="grey--text text--lighten-4">Blood Type</h6>
                  <h6 class="white--text">AB+</h6>
                </v-col>
              </v-row>
            </v-col>
          </v-row>
        </v-card>
      </v-col>
      <v-col cols="12" sm="3">
        <v-card color="transparent" class="rounded-lg mx-2 px-2" flat>
          <span class="caption grey--text mt-n6">Phone Number</span>
          <h5 class="black--text mb-7">+32 (0) 4973 342 542</h5>
          <span class="caption grey--text mt-n6">Card Number</span>
          <h5 class="black--text mb-7">77329</h5>
        </v-card>
      </v-col>
      <v-col cols="12" sm="5">
        <v-card color="transparent" class="rounded-lg mx-2 px-2" flat>
          <span class="caption grey--text mt-n6">Email</span>
          <h5 class="black--text mb-7">example@example.com</h5>
          <span class="caption grey--text mt-n6">Medical Condition</span>
          <h5 class="black--text mb-7">
            Alergies, Astma, Coronary Heart Disease
          </h5>
        </v-card>
      </v-col>
    </v-row>
  </v-card>
</template>

<script>
export default {
  name: "ContactView",
};
</script>

<style></style>
