

请求对象
GTVHttpRequest

``` javascript
{
  version:1.0,      // 接口版本
  module:"user",    // 模块名称
  method:"login",   // 方法名
  signature:"970d3198be85389ed7807d790370610f56cf71af", // 签名:用于验证客户端有权访问接口
  parameter:{ // 传递给服务器的参数，根据method的不同，parameters里面的内容不同.
    account:"account",
    password:"password"
  }
}
```

响应对象
GTVHttpResponse:
```javascript
{
  isSuccess:ture, // 如果请求成功，result为服务器返回的响应结果。如果服务器发生错误,error为服务器返回的错误信息。
  error: {
      code:225,
      message:"invalid request signature",
      url:"http://www.gtv.com/mobile/ios/help.html"
  },
  result:{
    /*json object returned by server*/
  }
}
```
---

参考链接:
> [来自HeroKu的HTTP API 设计指南(中文版)](http://get.jobdeer.com/343.get)
