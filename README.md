<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [Joomla](https://github.com/joomla/joomla-cms)

Joomla!是一套全球知名的内容管理系统，占有全球6%的网站市场份额。 Joomla!是使用PHP语言加上MySQL数据库所开发的软件系统。

## 部署

本项目基于开源应用中心 [oac](https://app.cloud.tencent.com/) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-Joomla&branch=master)
### 配置

- `MYSQL_CLIENT_DATABASE_HOST`：客户端数据库地址
- `MYSQL_CLIENT_DATABASE_PORT_NUMBER`：客户端数据库端口
- `MYSQL_CLIENT_DATABASE_ROOT_USER`：客户端数据库用户名
- `MYSQL_CLIENT_DATABASE_ROOT_PASSWORD`：客户端数据库密码
- `MYSQL_CLIENT_CREATE_DATABASE_NAME`：客户端创建的joomla数据库名
- `MYSQL_CLIENT_CREATE_DATABASE_USER`：客户端创建的joomla数据库用户
- `MYSQL_CLIENT_CREATE_DATABASE_PASSWORD`：客户端创建的joomla数据库密码
- `BITNAMI_DEBUG`：是否开启debug显示
- `ALLOW_EMPTY_PASSWORD`：是否允许密码为空
- `JOOMLA_DATABASE_TYPE`：数据库连接类型
- `JOOMLA_DATABASE_HOST`：joomla数据库地址
- `JOOMLA_DATABASE_PORT_NUMBER`：joomla数据库端口
- `JOOMLA_DATABASE_NAME`：joomla数据库名
- `JOOMLA_DATABASE_USER`：joomla数据库用户名
- `JOOMLA_DATABASE_PASSWORD`：joomla数据库密码
- `JOOMLA_USERNAME`：joomla后台用户名
- `JOOMLA_PASSWORD`：joomla后台密码

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
