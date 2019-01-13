<template>
  <div>
    <p>{{title}}</p>
    <hello-child message='This is a message' />
  </div>
</template>

<script>
  import HelloChild from './HelloChild'
  export default {
    data:() => {
      return {
        title: 'Hello World!'
      }
    },
    components:{
      HelloChild
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
