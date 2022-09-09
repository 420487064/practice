<template>
  <div class="hello">
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
    return{
      a:'1212'
    }
  },
  mounted(){
    this.c()
  },
  props: {
    msg: String
  },
  methods:{
    c(){
      var b = this.a
      b = '21231'
      console.log(b)
      console.log(this.a)
    }
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
