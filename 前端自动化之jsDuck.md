# 前端自动化之jsDuck
  
### 安装
- 问题一：安装出错
``` linux
fishdeMacBook-Pro:jsduck fish$ gem install jsduck
ERROR:  Could not find a valid gem 'jsduck' (>= 0), here is why:
          Unable to download data from https://rubygems.org/ - Errno::ECONNRESET: Connection reset by peer - SSL_connect (https://rubygems.org/latest_specs.4.8.gz)
````
解决方案：
```linux  
fishdeMacBook-Pro:jsduck fish$ sudo gem sources -a http://rubygems.org
Password:
https://rubygems.org is recommended for security over http://rubygems.org
Do you want to add this insecure source? [yn]  y
http://rubygems.org added to sources
#重新执行安装命令
fishdeMacBook-Pro:jsduck fish$ gem install jsduck
```
详情  
[http://stackoverflow.com/questions/19150017/ssl-error-when-installing-rubygems-unable-to-pull-data-from-https-rubygems-o](http://stackoverflow.com/questions/19150017/ssl-error-when-installing-rubygems-unable-to-pull-data-from-https-rubygems-o)
