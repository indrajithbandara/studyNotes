## 问题列表
> 使用官方方式创建项目，<code>npm start</code> 执行错误
```linux
ERROR  watchman--no-pretty get-sockname returned with exit code null dyld: Library not loaded: /usr/local/lib/libpcre.1.dylib
  Referenced from: /usr/local/bin/watchman
  Reason: image not found

Error: watchman--no-pretty get-sockname returned with exit code null dyld: Library not loaded: /usr/local/lib/libpcre.1.dylib
  Referenced from: /usr/local/bin/watchman
  Reason: image not found
```
```linux
TT:proj fish$ brew uninstall watchman
Uninstalling /usr/local/Cellar/watchman/3.2.0... (6 files, 200K)
TT:proj fish$ brew install --HEAD watchman
Error: You must `brew link pcre' before watchman can be installed
TT:proj fish$ brew link pcre
Linking /usr/local/Cellar/pcre/8.37...
Error: Could not symlink share/man/man3/pcre.3
/usr/local/share/man/man3 is not writable.
TT:proj fish$ whoami
fish
TT:proj fish$ sudo chown -R `whoami` /usr/local
#OK
```
  
  
  
  
  
