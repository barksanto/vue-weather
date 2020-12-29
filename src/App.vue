<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="search..."/>
      </div>
    </main>
  </div>
</template>

<script>


export default {
  name: 'App',
  data(){
    return{
      api_key: 'b7f7ba740725cadece7fa95b9c604600'
    }
  }
}
</script>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: 'montserrat', sans-serif;
  }

  #app{
    background-image: url('https://images.unsplash.com/photo-1592210454359-9043f067919b?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80');
  }
</style>
