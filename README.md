doc4doc
================================================================================

简介：

本项目是使用 Node 实现的一个轻量级 CMS (Content Managment System) 系统， 可以不加修改地运行在 BAE (Baidu App Engine) 之上。

虽然项目使用的是 BAE 限制的 Node 技术，然而并没有额外地使用任何 BAE 扩展，也就是说本应用是一个纯粹的 Node 应用，完全可以本地运行或是运行在其他 Node App Engine 之上。
    
项目本意是设计一个文档系统， 文档使用 project 作为划分大类、 tags 作为划分小类。文档的写作由注册用户完成， 所以本项目实际上是一个多人博客系统。 然而本应用又以用户为中心来管理文字、图片和文件，将来可能演化成一个 SNS 系统。

演示 ： http://newteck.duapp.com

功能 ：

1. 提供用户注册、登陆和退出，用户信息编辑功能；
2. 为注册用户提供文字编辑功能，图片上传和管理、普通文件上传和管理功能；
3. 按项目大类、标签小类管理用户的文字；
4. 按用户管理文字、图片和其他文件功能；
5. 系统上所有的内容对任何访问者都是 public 的；
6. 按用户组织编辑、修改和删除权限； 设有唯一的 admin 管理员；
7. 更多的功能有待 u 的挖掘 ...

注意 ：

1. 项目使用了一些 Node 模块，包括 express 、ejs 、mongodb 、formidable ，使用前先安装这些模块；
2. 项目使用的是 MongoDB 数据库，所以正常使用要安装 MongoDB 数据库；


