<template>
  <form class="q-pa-md">
    <div class="q-mb-sm">
      <q-input outlined v-model="name" label="Name" />
    </div>
    <div class="q-mb-sm">
      <q-input outlined v-model="email" label="Email" />
    </div>
    <div class="q-mb-sm">
      <q-input outlined v-model="latter" label="Name Latter" />
    </div>
    <q-btn
      color="primary"
      text-color="white"
      label="Add Contact"
      @click="submitData()"
    />
  </form>
</template>
 <script>
export default {
  emits: ["contact"],
  data() {
    return {
      name: "",
      email: "",
      latter: "",
    };
  },
  methods: {
    submitData() {
      this.$emit("contact", this.name, this.email, this.latter);
      // console.log("button is working");
    },
  },
};
</script>
<style>
</style>
