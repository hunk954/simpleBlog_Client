<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  <div>
      <el-input v-model="userID" placeholder="用户名" class='inputClass'></el-input>
   </div>
   <br>
   <div>
      <el-input v-model="password" placeholder="密码" class='inputClass' type='password'></el-input>
   </div>
   <br>
   <div>
    <el-button type="primary">登录</el-button>
  </div>
  </div>
  
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Sign in to Single Blog',
      userID: '',
      password: ''

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body{
  font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
}
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
.inputClass{
  width:300px
}
</style>
