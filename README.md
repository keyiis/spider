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
text:需要解析的包含unicode的字符串，例如 "销量:&#x0768e;月售&#x25E8F;"
```
**返回结果：**  
```
{
   status:,
   resp:"销量:2月售4"
}
```
# postman示例
![image](https://github.com/keyiis/spider/blob/main/postman-headers.png)  
![image](https://github.com/keyiis/spider/blob/main/postman.png)

# 本人微信号 keyiis2017
