Minecraft 地图画生成器
================

基于 [Node.js](https://nodejs.org/zh-cn/) 的用于转换图片至 Minecraft 地图的在线工具

使用的其他代码库
----------------
[jQuery](https://jquery.com/)
[bootstrap](https://github.com/twbs/bootstrap)
[Colour.js](http://stevehanov.ca/blog/index.php?id=116)
[cookies.js](https://github.com/ScottHamper/Cookies)
[node-nbt](https://github.com/djfun/node-nbt)
[archiver](https://github.com/ctalkington/node-archiver)
[babel](https://github.com/babel/babel)
[lazystream](https://github.com/jpommerening/node-lazystream)
[moment](https://github.com/moment/moment)
[node-static](https://github.com/cloudhead/node-static)
[winston](https://github.com/winstonjs/winston)

安装与运行
------------------------------------
1. 安装 [Node.js](https://nodejs.org/zh-cn/)
2. 下载该仓库中的所有文件
3. 使用 `npm install` 来安装依赖
4. （可选）使用 `npm test` 开启测试
5. 使用 `npm run build` 进行编译
6. （可选）复制 `public/`，`lib/` 和 `package.json` 到你的服务器，并且在服务器上运行 `npm install --production`
7. 使用 `npm start` 开启项目

如果暂时没有可用的服务器，可使用 [原作者的网站（英文）](http://mc-map.djfun.de) 进行测试


开源许可
--------
mc-map-item-tool 使用 MIT license 作为其开源许可。


测试
-----
使用以下命令开启测试：

    npm test
