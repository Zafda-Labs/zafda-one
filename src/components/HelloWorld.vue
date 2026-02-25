<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
We are building something better, stronger, and more thoughtful. <br>
Our next chapter is designed to redefine learning as an experience, not just content consumption. <br> <br>

The team is working diligently behind the scenes to bring this to life and go live at the earliest. <br>
Thank you for the trust, encouragement, and support you have shown us over the past few years. It means more than you know.<br> <br><br>

If you are a subscriber, please write to admin@zafda.one with your Subscriber ID <br> 
Our team will assist you promptly.<br>
      
    </p>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
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
