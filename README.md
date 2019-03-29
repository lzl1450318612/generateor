# byte-easy

#### 介绍
**byte-easy 代码+页面一键生成**
    本项目使用springboot集成mybatis-plus+framemaker框架，可以通过数据库对应的字段以及注释，生成相应的表的增删改查以及列表页，功能绑定完善。

#### 使用说明
   1、首先启动项目，本项目为spring boot项目，直接运行EasyApplication程序启动项目。<br/>
   2、运行CodeGenerator程序，依次输入包名、数据库表名、0（例如：admin、test、0）<br/>
   3、将expand中的controller替换掉我们的包（admin/test）下的controller<br/>
   4、将expand中的页面附带父文件夹复制到templates中。<br/>
   5、在浏览器输入localhost:8080,账号密码分别为admin 123456<br/>
   6、在权限管理中添加添加我们刚刚新建的controller的路由,父栏目选择“顶级栏目”，路由填写我们的controller的requestMapping值<br/>
   7、在角色管理中给管理员点击编辑，给当前用户角色添加上当前权限<br/>
   8、刷新页面