## 项目背景
由于公司开发的项目经常有一些相同的板块，如果每个项目都去开发同样的代码，多少显得有些冗余，不如把它们综合起来，做成一个统一的后台，这样就减轻了不少开发的时间，于是就诞生了此项目。

## 启动项目
1. 安装mysql，创建publicApi（此名称不固定，如需更改到`.env`配置文件中修改``DATABASE_NAME``）数据库
2. 去``.env``配置文件中将值为``xxx``的配置改为自己的
2. 在项目文件下运行``npm install``安装所需依赖
3. 运行``npm run start``或者``npm run dev``启动项目
