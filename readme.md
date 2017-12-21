
# 用户注册接口

* 用户注册

## 接口信息

>传入数据验证不重复后注册成功

### 请求

`POST/index.php/register`

字段|类型|含义
-|----|---
jscode|string|jscode

请求示例

<pre><code>{
	"jscode":"string"
}</code></pre>

### 响应

data

字段|类型|含义
---|---|---
jscode|string|用户信息

### 登录成功

<pre></code>{
	"status":0,
	"info":"登陆成功",
	"data":{
		"jscode":"xxxxxx"
	}
}</code></pre>
