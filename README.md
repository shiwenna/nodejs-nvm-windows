# nodejs-nvm-windows
nodejs version control


#nvm-windows安装
**注意：**在安装之前，需要卸载所有已存在的nodejs版本，包括nodejs安装目录（如："C:\Program Files\nodejs"）。NVM生成的连接不会覆盖现有的安装目录。
同时，也要删掉npm安装位置（如："C:\Users<user>\AppData\Roaming\npm"）这样NVM安装位置才会正确。安装完成后，需要为每一个node版本重新安装的全局模块（如：gulp））

`nvm use 4.4.0` `npm install gulp-cli -g` `nvm use 0.10.33` `npm install gulp-cli -g`


*  **安装** 

    下载最新版本，下载地址：https://github.com/coreybutler/nvm-windows/releases，解压安装。

*  **更新** 
   
    运行新的安装程序，安装程序会越过nodejs进行更新，确保使用之前的安装路径和文件夹。如果安装到默认位置只需单击“next”，直到安装结束。

*  **使用** 

    * `nvm install <version> [arch]`：安装指定版本的nodejs或‘latest’安装最新稳定版本。可选安装32位或64位版本，设置`[arch]`为‘all’安装32位和64位版本。
    * `nvm list [available]`：nodejs安装版本列表。`available`显示可下载版本列表。
    * `nvm on`：nodejs版本管理启用。
    * `nvm off`：nodejs版本管理禁用（不会卸载任何程序）。
    * `nvm uninstall <version>`：卸载指定版本nodejs。
    * `nvm use <version> [arch]`：切换到指定版本。可选32/64位。
    * `nvm version`：展示当前NVM版本。
    * `nvm node_mirror <node_mirror_url>`：设置node镜像。在中国可使用https://npm.taobao.org/mirrors/node/。
    * `nvm npm_mirror <npm_mirror_url>`：设置npm镜像。在中国可使用https://npm.taobao.org/mirrors/npm/。
    

