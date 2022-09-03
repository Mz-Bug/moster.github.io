<template>
  <q-page>
    <div>
      <card :progress1="progress1" :progress2="progress2"></card>
    </div>
    <div>
      <q-btn
        class="q-ml-md"
        color="primary"
        label="Attack"
        @click="monsterattack()"
      />
      <q-btn
        class="q-ml-sm"
        color="primary"
        label="Special Atack"
        @click="specialattack()"
        :disable="roundcouter"
      />
      <q-btn
        class="q-ml-sm"
        color="primary"
        label="Heal"
        @click="healplayer()"
      />
      <q-btn
        class="q-ma-md"
        color="primary"
        label="Surrender"
        @click="surrender()"
      />
    </div>
    <Text></Text>
  </q-page>
</template>
<script>
import { defineComponent } from "vue";
export default defineComponent({
  name: "PageIndex",
  data() {
    return {
      progress1: 1,
      progress2: 1,
      counter: 0,
    };
  },
  methods: {
    monsterattack() {
      this.counter++;
      const monsterhealth = Math.floor(Math.random() * (0.4 - 0.2)) + 0.3;
      this.progress1 = this.progress1 - monsterhealth;
      this.playerattack();
    },
    playerattack() {
      const playerhealth = Math.floor(Math.random() * (0.73 - 0.41)) + 0.41;
      this.progress2 = this.progress2 - playerhealth;
    },
    specialattack() {
      this.counter++;
      const specialattack = Math.floor(Math.random() * (0.7 - 0.5)) + 0.5;
      this.progress1 = this.progress1 - specialattack;
      this.playerattack();
    },
    healplayer() {
      this.counter++;
      const healplayer = Math.floor(Math.random() * (0.32 - 0.12)) + 0.12;
      this.progress2 = this.progress2 + healplayer;
    },
    surrender() {
      const surrender = Math.floor(Math.random() * (1 - 1)) + 1;
      this.progress2 = this.progress2 - surrender;
    },
  },
  computed: {
    roundcouter() {
      return this.counter % 3 !== 0;
    },
  },
  components: {
    Text: require("components/monster.vue").default,
    card: require("components/card.vue").default,
  },
});
</script>
<style lang="sass" scoped>
</style>

