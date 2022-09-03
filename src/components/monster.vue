<template >
  <q-page class="q-pa-md row items-start q-gutter-md">
    <q-input color="teal" filled v-model="text" label="Label">
      <template v-slot:prepend>
        <q-icon name="event" />
      </template>
    </q-input>
    <div>
      <q-btn
        to="/contact"
        :loading="loading[3]"
        color="primary"
        @click="simulateProgress(3)"
        style="width: 150px"
      >
        Button
        <template v-slot:loading>
          <q-spinner-hourglass class="on-left" />
          Loading...
        </template>
      </q-btn>
    </div>
  </q-page>
</template>

<script>
import { ref } from "vue";

export default {
  setup() {
    const loading = ref([false, false, false, false, false, false]);
    const progress = ref(false);
    function simulateProgress(number) {
      // we set loading state
      loading.value[number] = true;

      // simulate a delay
      setTimeout(() => {
        // we're done, we reset loading state
        loading.value[number] = false;
      }, 3000);
    }
    return {
      text: ref(""),
      loading,
      simulateProgress,
      progress,
    };
  },
};
</script>

 <style>
</style>
