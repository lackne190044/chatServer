<template>
  <div class="hello">
    <h1>Login</h1>
    <form action="./tmp.txt">
        <label for="username" name="username">username:</label>
        <input type="text" id="username" name="username"><br><br>

        <label for="password" name="password">password:</label>
        <input type="text" id="password" name="password"><br><br>

        <input type="submit" value="submit">
    </form>
  </div>
</template>

<script>
export default {
  name: 'UserLogin',
  props: {
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
