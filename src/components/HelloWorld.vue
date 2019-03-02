<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Hello Vue in CodeSandbox!</p>
    <h3>z</h3>
    <ul>
      <li>x</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  mounted() {
    console.log(process.env.NODE_ENV);
    console.log(process.env.VUE_APP_ONE);
    // console.log(process.env.TEST);
    // {{ one }}
  }
};
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
