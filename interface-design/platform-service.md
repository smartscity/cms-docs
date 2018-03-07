# Platform Service

### 平台微服务

* 服务一级命名：  ???
* 管理注册中心、配置中心、Gateway、UAA（用户认证授权中心）等服务

### 用户微服务

* URI：**/uaa**

* **NOT Login**

* 注册  
  1. /register

* 登录
  1. **/login**
* 退出
  1. /logout
* 重置
  1. /reset
* 图形验证码
  1. /graphcode
* 短信验证码
  1. /smscode
* 邮箱验证码
  1. /smscode

* **Login Required**

* 用户管理  
  1. /user

* 用户组管理
  1. /group
* 用户基本信息
  1. /user/baseinfo
* 签到
  1. /attendance
* 收藏
* 关注
* 代币
* 站内信
* 审计日志
* 应用管理
* 角色管理
* 资源管理

```yaml
# 1.登录
/login
# 2.退出

# 3.忘记密码
/forget
# 4.重置密码
/reset
# 5.注册
/register
# 6.图形验证码/
/graphcode
# 7.短信验证码/
/smscode
```



