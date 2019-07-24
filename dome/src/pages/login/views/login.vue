<template>
  <div id='userLogin'>
123123123
123123123
  </div>
</template>

<script>

  export default{
      data(){
          return{
              userInfo: {
                user: '',
                password: ''
              },
              userInfoValidate: {
                user: [
                  { required: true, message: '请输入用户名', trigger: 'blur' }
                ],
                password: [
                  { required: true, message: '请输入密码', trigger: 'blur' }
                ]
              }
          }
      },
      methods:{

      }
  }
</script>

<style scoped>
  #userLogin{
    width:100%;
    height:100%;
    display:flex;
    justify-content: center;
    align-items: center;
  }
  .userLogin{
    width:280px;
    padding:10px;
    background:rgba(0,0,0,0.3);
    border-radius:5px;
  }
  .loginButtonGroup{
    text-align:center;
    width:calc(100% - 20px);
  }
</style>
