# hpcs-gin
http://localhost:8080/user/register 注册
  使用json格式输入
  如{
    "username":"xxx",
    "password":"1111111"
  }//密码长度需要大于六
http://localhost:8080/user/login    登录
http://localhost:8080/user/:id      删除
  :id即为需要删除的用户名
http://localhost:8080/user/revise   修改密码
   直接用json输入用户密码即可，不需要旧密码
