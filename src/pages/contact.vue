<template>
  <q-page>
    <div class="q-pa-md">
      <q-toolbar class="bg-primary text-white shadow-2">
        <q-toolbar-title>Contacts</q-toolbar-title>
      </q-toolbar>
      <q-list bordered>
        <q-item v-for="contact in contacts" :key="contact.id" class="q-my-sm">
          <q-item-section avatar>
            <q-avatar color="primary" text-color="white">
              {{ contact.letter }}
            </q-avatar>
          </q-item-section>

          <q-item-section>
            <q-item-label>{{ contact.name }}</q-item-label>
            <q-item-label caption lines="1">{{ contact.email }}</q-item-label>
          </q-item-section>

          <q-item-section side>
            <q-icon name="close" color="red" />
          </q-item-section>
        </q-item>
        <addcontact @contact="newcontact"></addcontact>
      </q-list>
    </div>
  </q-page>
</template>
<script>
export default {
  data() {
    return {
      contacts: [
        {
          id: 1,
          name: "Ruddy Jedrzej",
          email: "rjedrzej0@discuz.net",
          letter: "R",
        },
        {
          id: 2,
          name: "Mallorie Alessandrini",
          email: "malessandrini1@marketwatch.com",
          letter: "M",
        },
        {
          id: 3,
          name: "Elisabetta Wicklen",
          email: "ewicklen2@microsoft.com",
          letter: "E",
        },
        {
          id: 4,
          name: "Seka Fawdrey",
          email: "sfawdrey3@wired.com",
          letter: "S",
        },
      ],
    };
  },
  components: {
    addcontact: require("components/add-contact.vue").default,
  },
  methods: {
    newcontact(name, email, latter) {
      const newfriendcontact = {
        id: new Date().toISOString(),
        name: name,
        email: email,
        letter: latter,
      };
      this.contacts.push(newfriendcontact);
    },
  },
};
</script>
<style>
</style>
