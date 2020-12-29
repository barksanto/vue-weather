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
    background-size: cover;
    background-position: bottom;
    transition: 0.4s;
  }

  main{
    min-height: 100vh;
    padding: 25px;
    background-image: linear-gradient(to bottom, rgba(0,0,0,0.25), rgba(0,0,0,0.75) );
  }

  .search-box{
    width: 100%;
    margin-bottom: 30px;
  }

  .search-box .search-bar {
    display: block;
    width: 100%;
    padding: 15px;
    color: #313131;
    font-size: 20px;
    appearance: none;
    border: none;
    outline:none;
  background-color: rgba(255, 255, 255, 0.15);
  }
</style>
