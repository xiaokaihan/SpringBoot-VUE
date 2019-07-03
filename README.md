# SpringBoot-VUE
**SpringBoot**整合**VUE**， 前后端不分离的案例

1. 先创建一个基于SpringBoot框架的hello-world项目（对应的une-gateway工程）；
2. 通过vue cli 创建一个hello-world项目（对应的是une-gateway-vue工程），创建轻教程：[](https://github.com/xiaokaihan/VUE)
3. 通过`npm install`，安装vue所需的依赖
4. 通过`npm run build`, 构建项目的静态文件。文件夹dist中即为静态页面文件。
5. 在springboot项目的resources文件夹中创建static文件夹
6. 将vue项目中的dist目录下的静态文件copy到springboot工程的static路径下即可
7. 启动springboot 项目， 通过localhost:port，即可访问vue页面