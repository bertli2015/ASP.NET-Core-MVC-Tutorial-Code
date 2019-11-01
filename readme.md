# Asp.net core mvc
### .net core 2.1请求通道
浏览器请求 --> IIS(web server 反向代理) --> .net core CLR --> web应用kestrel --> 管道 --> 请求处理，返回数据

### .net core 2.2
- 1.HostModel
    - InProgress|outofprogress
    - 默认配置：kestrel web server; asp.net core 内置跨平台
- 2.IIS
    - useIIs()、useIIsInlegration()
- 3.Log
- 4.IConfiguration接口，配置信息顺序如下，后者将覆盖前者:
    - appsettings.json
    - user secrets
    - 环境变量
    - 命令行参
- 5 
    - 管道和中间件, Logger <->授权<->
    - 路由, convention Routing/ Attribute Routing
- 6.controller
- 7.输出Model, TagHelper, URLHelper
- 8.输入Model, form
- 9.Data Annotions
- 10集成EF.core
- 11.view razor
- 12.TagHelper
- 13.引用前端文件， 前端验证
- 14.asp.net core Identity
- 15.授权认证
- 16.role manager
- 17.基于claim的授权
- 18.基于claim的授权
- 19.预防xss\csrf(跨站请求伪造)
- 20.Modelbing
- 21.Model验证
- 22.TagHelper
- 23.TagHelper compant
- 24.log
- 25.Filter Mvc
- 26.缓存，压缩
- 27.VSTS Aure devops CI/CD
