<template>
  <div class="counter">
    <h1>Counter</h1>
    <h1>{{ counter }}</h1>
    <button @click="counter +=1">Add</button> <button @click ="counter -=1">Subtract</button>
  </div>
</template>

<script>
export default {
  name: 'Counter',
  props: {
  },
  data(){
    return{
        counter: 0
        }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
