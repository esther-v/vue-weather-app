<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search..."/>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app',
  data(){
    return{
      api_key: '488a87570b1e8e64f249ce4a35195a9e'
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

body{
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}

#app{
  background-image: url('./assets/cold-bg.jpeg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}

main{
  min-height: 100vh;
  padding: 25px;
  background-image: linear-gradient(to bottom, rgba(0,0,0,0.25), rgba(0,0,0,0.75));
}

.search-box{
  width: 100%;
  margin-bottom: 30px;
}

.search-bar{
  display: block;
  width: 100%;
  padding: 15px;
}

</style>
