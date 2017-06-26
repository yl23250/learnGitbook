
# 1.跳转供应链
## 1.1API名称
> 方法名:ypt.open.user.gotoScmpPoint
>

>返回参数

| 参数名    | 参数类型     |
| :------------- | :------------- |
| code       | String      |
| message       | String   |
| data       | Object   |
>返回格式

~~~json
{
	"data": {
		"targetUrl": "http://scmp.dev.cloudyigou.com"
	},
	"code": "SUCCESS"
}
~~~


>返回异常
>

| 异常编码   | 异常信息     |
| :------------- | :------------- |
| 20516     |获取供应链平台端地址失败     |

>返回格式

~~~json
{"code":"20516","message":"获取供应链平台端地址失败!"}
~~~


# 2.跳转基础库

## 1.1API名称
> 方法名:ypt.open.user.gotoBasicPoint
>
>返回参数

| 参数名    | 参数类型     |
| :------------- | :------------- |
| code       | String      |
| message       | String   |
| data       | Object   |
>返回格式

~~~json
{
	"data": {
		"targetUrl": "http://basic.dev.cloudyigou.com"
	},
	"code": "SUCCESS"
}
~~~

>返回异常
>
| 异常编码   | 异常信息     |
| :------------- | :------------- |
| 20516     |获取基础库地址失败!      |
>返回格式

~~~json
{"code":"20516","message":"获取基础库地址失败"}
~~~
