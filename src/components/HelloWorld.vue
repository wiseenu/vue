<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      At this portofolio you will found some of my mini project 
    </p>
    <ul>
      <p>
      So, Wellcome to my portofolio and i hope you like my portofolio
      </p>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
  font-size: 30px;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
