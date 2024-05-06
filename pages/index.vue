<template>
  <v-container fluid fill-height>
    <v-row align="center" justify="end" style="height: 150px" no-gutters>
      <v-col cols="6">
        <v-sheet class="pa-2">Welcome To Landing Page 1</v-sheet>
      </v-col>
      <v-col cols="6">
        <v-sheet class="pa-2">
          <v-btn
            color="primary"
            :to="{
              name: 'Login',
            }"
            >Login</v-btn
          >
        </v-sheet>
      </v-col>
    </v-row>
  </v-container>
</template>
<script setup lang="ts"></script>
