<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <p>
  <router-link to="/">home</router-link> |
  <router-link to="/about">about</router-link>
  </p>
  <router-view></router-view>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>
