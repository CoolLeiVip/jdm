# jdm
线报监控专用，纯收集，无审查

ql repo https://github.com/6dylan6/jdm.git "jd_" "" "^jd[^_]|USER|function|sendNotify|magic|h5sts|utils"

##一些变量（没写的看脚本内注释）

1、自定义sign

```
export JD_SIGN_API='url'
```

2、代理API(3个全配置)

```
export JD_COMMON_REQUEST_HTTP_DYNAMIC_PROXY_API='url'
export RS_ISV_TOKEN_PROXY_API="url"
export RS_PROXY_API="url"
export RS_API_WHITELIST="jd_"

```
3、代理池模式

```
export RS_PROXY_TUNNRL="http://xxx"
export RS_TUNNRL_WHITRLIST="jd_"
export RS_ISV_TOKEN_PROXY_TUNNRL="http://xxx" 
```


4、自动填地址（报错就是变量不对，或者删除变量）


```
export WX_ADDRESS="" # 变量格式：收件人@手机号@省份@城市@区县@详细地址@6位行政区划代码@邮编，需按照顺序依次填写，多个用管道符分开（6位行政区划代码自己查地图，也可用身份证号前六位）
export WX_ADDRESS_BLOCK="" # 黑名单关键词，多个关键词用@分开
```


