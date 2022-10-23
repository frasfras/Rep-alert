<template>

  <div class="hello">
  <h1>{{ msg }}</h1>Manual Control
   <div class="input m-4">
 
  </div>
  </div>
</template>

<script>
//import { ToggleButton } from 'vue-js-toggle-button';

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
    ToggleButton
  },
   data() {
    return {
      gpu: false,
      fairw: false,
      cpu: false,
      green: false
    };
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
