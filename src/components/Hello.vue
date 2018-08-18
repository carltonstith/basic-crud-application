<template>
  <div class="hello">
    <div class="hero">
      <div>
        <h1 class="display-3">Hello World</h1>
        <p class="lead">This is the homepage of your vue app</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1, h2 {
  font-weight: normal;
}
.hero {
  height: 90vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}
.hero .lead {
  font-weight: 200;
  font-size: 1.5rem;
}
</style>
