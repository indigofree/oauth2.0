# oauth2.0
这是一个OAuth2.0的客户端的动态web项目。
主要演示的是authorization_code方式授权。


oauth2ClientGoogle.config配置文件配置问题

1、使用谷歌控制台申请客户端id
   https://console.developers.google.com/apis 选择凭据(credentials)创建新的凭据。
注意：创建凭据的名称要与项目名称一致，否则生成的client_id无效。
     如果是第一次创建凭据，则需要修改OAuth同意屏幕标签下的内容。
     本人项目生成的 
     client_id=204022646354-pmomgjh4cv11anvvj5hc0mt1mhnipth7.apps.googleusercontent.com 
     client_secret=nlWIz17Yt9skhoNVRKUxw7cF
2、确保resource server uri 中的资源API是enable状态。
https://console.developers.google.com/apis 中选择所要获取信息的api，然后启动。
