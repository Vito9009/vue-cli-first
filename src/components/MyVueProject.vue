<template>
  <div class="jumbotron">
      <h1>La mia prima app con Vue CLI!</h1>
  </div>
</template>

<script>
export default {
  name: 'MyVueProject',
}
</script>

<style scoped>
.jumbotron {
    height: 700px;
    min-height: 700px;
    background-size: cover;
    background-position:center;
    background-image: url(https://www.laramind.com/blog/wp-content/uploads/2019/09/1_RQN0D9NAO0nrn3DrllefXg.png);
}

h1{
  padding: 50px 0;
}
</style>