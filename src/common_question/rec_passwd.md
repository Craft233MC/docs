---
title: 忘记登陆密码
copyright: 使用 <a href="https://theme-hope.vuejs.press/zh/" target="_blank">VuePress Theme Hope</a> 主题 | Copyleft© 2023 Craft233  <a href="https://icp.gov.moe/?keyword=20232336" target="_blank">萌ICP备20232336号</a>
order: 2
---
## 介绍
忘记了登陆密码怎么办？知道注册时的邮箱就行  
邮箱以注册时为准
## 解决办法
### 1.获取验证码
指令输入
```
/email recover <注册时的邮箱>
```
会发送一封带有验证码的邮箱到你的账户  
比如说我设置的是<code>zhangsan@testmail.com</code>
则输入<code>/email recover zhangsan@testmail.com</code>
然后检查你的收件箱(没有请检查垃圾邮箱)
### 2.验证
按照邮箱里的命令输入邮箱  
比如
```
/email code 114514
```
其中<code>114514</code>为邮箱内的验证码  
验证码旁也有完整命令
### 3.修改密码
通过验证后会要求修改密码   
按照要求来即可  
指令一般为<code>/email setpassword <要设置的密码></code>  
比如设置密码为<code>1141541919810</code>
```
/email setpassword 1145141919810
```
### 4.登陆
使用修改后的密码登陆即可

## 无法使用？
如果不能常规方法恢复，请联系腐竹
