cd video

apt-get update 

//Node のインストール

sudo apt-get install nodejs  

//Node パッケージ管理のインストール 

sudo npm install  

//node コマンドを使用できるようにする 

sudo update-alternatives --install /usr/bin/node node /usr/bin/nodejs 10   

//Node パッケージ管理の初期化

npm init  

//socket.io パッケージのインストール 

npm install socket.io  

apt-get install nodejs npm 
 
//n package のインストール 

npm cache clean npm install –g n 
 
※n package のインストールで失敗した場合は、以下の設定を行ってください。

npm config set strict-ssl false

sudo npm install –g n 

npm config set strict-ssl true 

sudo node server/server.js
