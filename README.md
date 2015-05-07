

GTVHttpRequest:
``` javascript
{
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
      code:225
      message:"invalid request signature"
  },
  result:{
    /*json object returned by server*/
  }
}
```
