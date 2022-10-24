## git代理使用

### 使用问题
- 问题1：Received HTTP code 407 from proxy after CONNECT
解决方法：

```
git config --global http.proxy http://username:password@ip:port
git config --global https.proxy http://username:password@ip:port
git config --global https.sslVerify false
```

