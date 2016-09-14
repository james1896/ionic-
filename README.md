# ionic-




cordova + ionic 

1.node.js 安装
2.sudo nam install -g cordova

cordova create hello com.test.helloWorld HelloWorld
cordova platform add ios

3.sudo npm install -g cordova ionic

ionic start myApp tabs
ionic start myApp blank
ionic start myApp sidemenu
三种模版

可能存在问题 
使用 ionic info 查看ionic是否完全安装

如果没有成功安装 按照命令指示 继续安装

如果sudo npm install -g ios-deploy 报错
该用下面方法尝试
sudo npm install -g ios-deploy --unsafe-perm=true
