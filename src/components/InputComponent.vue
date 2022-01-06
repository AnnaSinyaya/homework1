<template>
    <div class="example">
            <input type="text" v-bind:value="name" v-on:input="name = $event.target.value">
            <hr>
            <h2>Hello, {{ name }}!</h2>
    </div>
</template>

<script>
export default {
  name: 'InputComponent',
  data () {
    return {
      name: 'Vue.js'
    }
  }
}
</script>

<style scoped>
.example {
  width: 70%;
  margin: 20px auto;
}

h2 {
  font-weight: normal;
  font-size:28px;
  color: #42b983;
}
</style>
