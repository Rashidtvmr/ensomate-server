<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar >
     <q-btn
      @click="$q.notify('My message')"
      color="primary"
      label="Show a notification"
    />
    <q-item>
      <q-item-section tag="a" to="/login"></q-item-section>
      <q-item-label>Login</q-item-label>
    </q-item>

        <q-btn v-touch-swipe="handler" color="deep-orange" to="/login" glossy label="Deep Orange" />
      </q-toolbar>

    </q-header>
    <q-page-container>
      <router-view/>
    </q-page-container>
  </q-layout>
</template>

<script>
import { openURL } from 'quasar';

export default {
  name: 'MyLayout',
  data() {
    return {
      leftDrawerOpen: this.$q.platform.is.desktop,
    };
  },
  methods: {
    openURL,
  },
};
</script>

<style>
</style>
