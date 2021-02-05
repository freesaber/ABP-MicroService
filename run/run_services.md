1. cd ../BaseService/BaseService.Host

2. cd  ../AuthServer/AuthServer.Host

3. cd ../MicroServices/Business/Business.Host

4. cd ../MicroServices/FileStorage/FileStorage.Host

5. cd ../Gateways/WebAppGateway/WebAppGateway.Host

## 说明
在vscode中打开run目录，然后打开5个终端，每个终端进入一个项目，通过dotnet watch  run启动每个项目。
这样如果需要调试某个项目，之间在终端中停止，然后通过vs启动项目即可。另外，这样只需一个vs窗口即可管理这些项目启动

## 问题
1.
npm install node-pre-gyp 

2.
找不到 vendor
Module build failed: Error: ENOENT: no such file or directory, scandir '/home/vagrant/Code/sample/node_modules/node-sass/vendor'

使用 npm 重新生成 node-saaa

npm rebuild node-sass --no-bin-links