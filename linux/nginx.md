##安装

- http://nginx.org/en/download.html下载http://nginx.org/download/nginx-1.2.0.tar.gz
- tar -xf nginx-1.2.0.tar.gz
- 进入解压目录  chmod a+rwx *
- ./configure --without-http_rewrite_module
- make && make install
- sudo /usr/local/nginx/sbin/nginx
- 浏览器访问 localhost
