<template>
  <div id="app">
    <section class="jumbotron text-center">
      <div class="container">
        <h1 class="jumbotron-heading">Vue with Bootstrap Alerts</h1>
        <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />
        <p class="lead text-muted">
          A quick demo leveraging Vue alongside Bootstrap alerts to display different types of notifications.
        </p>
      </div>
    </section>
    <Notifications type="alert-primary">
        This is a primary alert with <a href="#" class="alert-link">an example link</a>.
    </Notifications>
    <Notifications type="alert-secondary">
        This is a secondary alert with <a href="#" class="alert-link">an example link</a>.
    </Notifications>
    <Notifications type="alert-success">
        This is a success alert with <a href="#" class="alert-link">an example link</a>.
    </Notifications>
    <Notifications type="alert-danger">
        This is a danger alert with <a href="#" class="alert-link">an example link</a>.
    </Notifications>
    <Notifications type="alert-warning">
        This is a warning alert with <a href="#" class="alert-link">an example link</a>.
    </Notifications>
    <Notifications type="alert-info">
        This is a info alert with <a href="#" class="alert-link">an example link</a>.
    </Notifications>
    <Notifications type="alert-light">
        This is a light alert with <a href="#" class="alert-link">an example link</a>.
    </Notifications>
    <Notifications type="alert-dark">
        This is a dark alert with <a href="#" class="alert-link">an example link</a>.
    </Notifications>
  </div>
</template>

<script>
import Notifications from './components/Notifications.vue'

export default {
  name: 'App',
  components: {
    Notifications
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
