<template>

  <div class="headerStyle">
    <header>
        <h1>{{ msg }}</h1>
         <ul style="color:white">
          <li>
            <router-link to="/" exact> 
            <button>List</button> </router-link>
          </li>
          <li>
            <router-link to="/add" exact><button>Add Item</button> </router-link>
          </li>
    </ul>
    
    </header>

   
  </div>
</template>

<script>
export default {
  
  data(){
    return{
        msg: 'Singapore Attractons List'
        }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header{
    background:rgb(122, 63, 100);
    padding:10px;
    border-style: solid;
    border-color:black;
    border-width: 2px;
}
h1{
    color:ivory
}
</style>