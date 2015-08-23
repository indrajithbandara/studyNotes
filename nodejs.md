#nodejs学习笔记
## npm 常见命令

+ npm install packageName //安装包
``` nodejs
直接使用npm install 命令会更具package.json文件的dependencies项的依赖来安装
-g 安装到全局，代码中不能通过require获取，一般用作命令行操作 如 npm intall -g forever
-save 安装包到包含package.json文件的项目目录中
-save-dev 安装到
```
+ npm list //参看当前目录安装包
+ npm help forever //参看forever命令的帮助信息
+ npm view forever dependencies //查看forever包的依赖关系
+ npm view forever repository.url //查看forever包源文件地址
+ npm outdated //查看所有npm所有过期的包，需要更新
+ npm update moduleName //更新包
+ npm uninstall moduleName //卸载包
+ npm search moduleName //查看包是否存在
+ npm init //引导创建package.json文件
+ npm root //查看当前包安装的目录
``` nodejs
npm root -g //查看包全局安装的目录
```
##### npm -v //查看npm版本
