<template>
  <div class="q-pa-md row items-start q-gutter-md">
    <q-card class="my-card">
      <q-card-section class="bg-primary text-white">
        <div class="text-h6">Monster Health</div>
      </q-card-section>
      <q-separator />
      <div class="q-pa-md bg-grey-10 text-white">
        <q-linear-progress
          dark
          stripe
          rounded
          size="20px"
          :value="progress1"
          color="red"
          class="q-mt-sm"
        />
      </div>
    </q-card>
    <q-card class="my-card">
      <q-card-section class="bg-primary text-white">
        <div class="text-h6">Your Health</div>
      </q-card-section>

      <q-separator />
      <div class="q-pa-md bg-grey-10 text-white">
        <q-linear-progress
          dark
          stripe
          rounded
          size="20px"
          :value="progress2"
          color="red"
          class="q-mt-sm"
        />
      </div>
    </q-card>
  </div>
</template>
<script>
export default {
  props: ["progress1", "progress2"],
  data() {
    return {
      // progress1: 1,
      // progress2: 1,
    };
  },
};
</script>
<style lang="sass" scoped>
.my-card
  width: 100%
</style>
