
<template>
  <div class="greetings">
    <h1 class="green">{{ msg }} {{youName()}}!</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: "Hello"
    }
  },

  methods:{
    youName(){
        return "Tiago";
    }
  },
}
</script>

<style scoped>
</style>
