启程后台通用底层系统
====================

qc-base是基于[Yii2](https://github.com/yiisoft/yii2/)框架实现的通用底层系统，旨在于构建一个代码风格良好、注释清晰可读、
功能稳定强大、可维护性以及可扩性较强的通用系统，以最大化提升程序开发的效率和乐趣。


环境要求
--------

Web服务器需要支持 **PHP 5.4.0.** 及以上


功能列表
--------

### 整体功能：

- 用户管理
- 角色管理
- 菜单管理
- 表单管理
- 消息管理（站内消息、邮件、短信等）
- 配置管理
- 附件管理
- 系统日志
- 模块管理

### 表单管理功能点：

- 支持字段权限设定
- 支持关联表
- 设置字段说明
- 列表显示字段自定义（是否显示、宽度设定：百分比和定宽）
- 列表排序自定义
- 搜索字段自定义，支持高级搜索
- 新增、修改页面操作后能选择停留在当前页或返回原列表页
- 支持导入导出功能，导出功能要能生成导入模板下载
- 上传功能优化：在客户端判断文件大小等
- 支持字段分类，可分为基本信息、工作信息等分类
- 新增和修改页面里的字段分两栏显示
- 支持操作自定义：系统可默认开发查看、修改、删除、审核、发邮件、发短信、打印等操作，列表里需要什么操作可以根据需求选择
- 支持简单的审核流程
- 支持列表模板的选择：普通列表和树状列表等
- 支持数据合并
- input框等采用控件形式开发，方便拓展和维护


开发者须知
----------

### 代码规范

开发者应十分重视一个项目代码的规范和可读性，我们要求代码要遵循[PSR](http://www.php-fig.org/)规范和
[YII CORE CODE STYLE](https://github.com/yiisoft/yii2/blob/master/docs/internals/core-code-style.md)，
每个参与到项目的人员都要为自己所写的代码添加清晰易读的注释，注释统一采用[Markdown](http://www.markdown.cn/)
语法来排版[phpDoc](http://phpdoc.org/)注释。如若不能达到规范要求，所提代码将不予合并。
