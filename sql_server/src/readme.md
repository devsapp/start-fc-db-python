# 阿里云函数计算 Python 访问 sql server 数据库

只需几步就可以快速在阿里云函数计算服务上体验 Python 访问 mysql 数据库

- 初始化项目：`s init start-fc-sql-server-python -d start-fc-sql-server-python`
- 进入项目：`cd start-fc-sql-server-python`
- 将 s.yaml 中的环境变量修改成您自己的值, 并将数据库操作代码改成您需要的
- 构建项目：`s build --use-docker`
- 部署项目：`s deploy`
- 触发项目：`s invoke`

即可实现`Python 访问 sql server`案例的初始化、部署整个流程。