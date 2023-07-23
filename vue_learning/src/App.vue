<template>
    <h3>vue初体验</h3>
    <p>{{ msg }}</p>
    <p>{{ num+1 }}</p>
    <p>{{ ok?"yes":"no" }}</p>
    <p>{{ message.split("").reverse().join("") }}</p>
    <p>{{ rawHTML }}</p>
    <p v-html="rawHTML"></p>
</template>

<script>
  export default{
    data(){
      return {
        msg:"helloworld",
        num:10,
        ok:true,
        message:"大家好",
        rawHTML:"<a href='http://www.baidu.com'>百度链接</a>"
      }
    }
  }
</script>

