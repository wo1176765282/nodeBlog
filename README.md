# nodeBlog
:memo: NodeJS博客系统（Beta 0.0.1）

采用Node.js编写的博客系统，bootstrap风格

## 预览

![](./screenshot.png)

## 功能

目前暂只实现了如下功能：

1. 首页展示文章
2. 文章分页
3. 管理文章
4. 管理评论

## 使用

1. 安装
    ```
    $ npm install
    ```

2. 创建数据库
    + 创建MySQL数据库，简历名为blog的数据库
    + 执行sql目录下的sql脚本创建初始化数据
    + 自定义数据库信息：修改`models/db.js`
    
3. 访问
    + 首页：`http://127.0.0.1:3001/index/1`,最后的数字为页码
    + 管理后台：`http://127.0.0.1:3001/admin/index`
