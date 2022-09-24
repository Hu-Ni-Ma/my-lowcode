# 一个demo版的低代码平台，目前只支持文本组件

## 一、技术选型

- 编程语言：typescript
- 前端框架：react
- 拖拽库：react-dnd
- 前端包管理工具：pnpm
- 打包工具：webpack
- 后端框架：koa
- 部署工具：pm2
- 格式化代码：prettier

## 二、目录结构

| 文件目录         | 说明                               |
| ---------------- | ---------------------------------- |
| ./README.md      | 说明文档                           |
| ./package        | 源代码                             |
| ./package/client | 前端源代码                         |
| ./package/server | 后端源代码                         |

## 三、开发指南

`bootstrap`：安装 pnpm 和 pm2
`pnpm install`：安装相关依赖
`dev:all`：本地开发，访问`localhost:8080`即可
`build:all`：打包构建
`format`：格式化代码

## 四、部署指南

`bootstrap`：安装 pnpm 和 pm2
`start`：启动服务
