# woff文件解析接口
**接口路径：** http://spider.keyiis.com/woff/parse  
**请求方式：** post  
**请求头(headers)：**   
```
id:加微信获取
key:加微信获取
```
**请求参数(body)：**  
```
remoteWoffUrl:woff文件的远程地址，必须是包含http或https的完整路径
unikeys:需要解析的unicode字符数组，例如 ["&#x0768e;","&#x25E8F;"]
```
**返回结果：**  
```
{
   status:,
   resp:{
      "&#x0768e;":"1",
      "&#x25E8F;":"2"
   }
}
```
# postman示例
![image](https://github.com/keyiis/spider/blob/main/postman-headers.png)  
![image](https://github.com/keyiis/spider/blob/main/postman.png)

# 本人微信号 keyiis2017
