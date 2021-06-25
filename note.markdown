## 常见问题小解

### windows
#### 端口被占用，关闭端口
- 查找端口netstat -ano|findstr "端口号"
- taskkill -F /pid 进程id

### git
###  push 或 clone 提示报错：fatal: unable to access '××': OpenSSL SSL
> windes 系统： cmd -> ipconfig /flushdns

### eclipse
#### 堆内存溢出异常 java.lang.OutOfMemoryError: Java heap space
- eclipse中的window-->Preferences-->Java-->Installed JREs --->Edit  在Default VM Arguments 中设置 ：“-Xms256M -Xmx512m” 
