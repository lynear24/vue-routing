<template>
  <div class="content">
    <header>
      <h1>{{ title }}</h1>
    </header>

    <div class="body">
      <a href="mailto:nylemaliwat@gmail.com"><h3>nylemaliwat@gmail.com</h3></a>
      <a href="https://lynear24.github.com"><h3>github.com/lynear24</h3></a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'contact',
  data () {
    return {
      title: 'Contact'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>