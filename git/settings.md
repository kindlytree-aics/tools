## git代理使用

### 使用问题
- 问题1：Received HTTP code 407 from proxy after CONNECT
解决方法：

```
git config --global http.proxy http://username:password@ip:port
git config --global https.proxy http://username:password@ip:port
git config --global https.sslVerify false
```
- 问题2：fatal: unable to access 'https://github.com/kindlytree-aics/tools.git/': Received HTTP code 502 from proxy after CONNECT
解决方法：
```
unset  HTTP_PROXY HTTPS_PROXY http_proxy https_proxy
```
- github push时的用户名密码问题
解决方法：密码使用token

- 问题2：git config使用问题
```
git config --local user.email kindlytree@163.com
git config --local user.name kindlytree
```