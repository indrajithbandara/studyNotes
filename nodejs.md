#nodejs学习笔记
## npm 常见命令

 npm install 安装包
  直接使用npm install 命令会更具package.json文件的dependencies项的依赖来安装
  -g 安装到全局，代码中不能通过require获取，一般用作命令行操作 如 npm intall -g forever
  -save 安装包到包含package.json文件的项目目录中
  -save-dev 安装到
