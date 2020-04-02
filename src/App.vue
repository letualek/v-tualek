<template>
  <div id="app">
    <h1>Well come to my web</h1>
    <h3>At first time</h3>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <label for="">Your Name
      <input v-model="message">
    </label>
    <button type="submit">Submit</button>
    <p >Hi {{message}} nice to meet you.</p>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {

  data:function () {
   return {message: ''
  }
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
