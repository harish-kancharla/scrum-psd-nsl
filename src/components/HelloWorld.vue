<template>
  <div class="container">

    <nav class="navbar navbar-default">
      <div class="container-fluid">
        <div class="navbar-header">
          <ul class="nav navbar-nav">
            <li class="active"><a href="#">Home</a></li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="jumbotron">
      <h1>Hello, world!</h1>
    </div>
    <div class="row">
        <div class="col-md-12">Lorem ipsum ...</div>
    </div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
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
