

GTVHttpRequest:
``` javascript
{
  version:1.0,
  module:"user",
  method:"login",
  signature:"970d3198be85389ed7807d790370610f56cf71af",
  parameter:{
    account:"account",
    password:"password"
  }
}
```

GTVHttpResponse:
```javascript
{
  isSuccess:ture,
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

> [来自HeroKu的HTTP API 设计指南(中文版)](http://get.jobdeer.com/343.get)
