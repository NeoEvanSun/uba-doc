#前端集成工具uba文档

##uba介绍:
uba is a front-end develop tool which consist of initialize,local service,mock server,deploy. Just 5 command then the development can be done. lite and simple.

##GET STARTED
全局安装uba

    npm install uba -g
执行 uba 或 uba -h 或 uba --help,查看 uba 所提供的指令

    uba
![alt text][id]

[id]: ./images/order_list.png "指令集"
执行list指令查看可用模板

    uba list
![alt text][id1]

[id1]: ./images/uba_list.png "指令集"
选择以iuap为模板,初始化项目
    
    uba init iuap web01
![alt text][id2]

[id2]: ./images/uba_init.png "指令集"
uba init 为 uba 的指令之一,负责初始化web工程,iuap 为 uba-template 的多套模板之一, web01 为项目名称

进入 web01 文件夹,安装依赖

    cd web01
    npm install



