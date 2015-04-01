####基本MVC架构
MVC是一种开发web应用程序的软甲模式架构，主要有三部分组成：
- **Model：**位于模式的最底层，主要负责操作数据
- **View：**主要用于向用户展现数据
- **Controller：**位于Model和View之间，控制Model层和View层之间的交互。

![MVC](http://www.tutorialspoint.com/images/struts-mvc.jpg)

#####The model
model层负责管理应用程序的数据。一方面响应来自于view层的请求，一方面响应来自controller层的指令去更新自身。

#####The view
以特定的格式展现数据，常见的视图层技术有JSP，ASP，PHP，且易于和Ajax集成。

#####The controller
controller层用于响应用户的输入和执行数据模型对象上操作。controller层接收用户输入，验证用户输入，执行逻辑操作从而修改对象模型的状态。
