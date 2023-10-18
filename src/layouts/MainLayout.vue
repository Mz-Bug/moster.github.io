<template>
  <q-layout view="lHh lpR fFf ">
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>
<script>
import { ref } from "vue";

export default {
  setup() {
    return {
      tab: ref("home"),
    };
  },
};
</script>
