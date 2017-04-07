<template>
  <div class="test">
    <h1>my first vue</h1>
    <input type="text" v-model="msg" placeholder="changemsg">
    <p>{{msg}}</p>
  </div>
</template>

<script>
  export default {
    name: 'test',
    data () {
      return {
        msg: 'Hello Vue!'
      }
    }
  }
</script>

<style>
body{
  font-family: "microsoft yahei";
}
</style>
