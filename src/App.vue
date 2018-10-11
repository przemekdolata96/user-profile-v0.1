<template>
  <div id="app">
    <UserProfile/>
  </div>
</template>

<script>
import UserProfile from './components/UserProfile.vue';

export default {
  name: 'app',
  components: {
    UserProfile,
  },
};
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Montserrat:300,400,600,700&subset=latin-ext');

* {
  margin: 0;
  padding: 0;
  font-family: Montserrat;
}

#app {
  margin-top: 60px;
  display: flex;
  justify-content: center;
  min-height: 1000px;
}
</style>
