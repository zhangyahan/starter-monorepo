# monorepo 项目脚手架

> 主要解决多个兄弟项目使用相同内部统一代码的解决方案

## 目录结构
```jsonc
|- apps // 项目
|- packages // 依赖
```

## 开发指南

### 整体开发模型
- 运行根目录下 `package.json` 中的 `dev:packages` 命令对通用模块进行启动
- 运行根目录下 `package.json` 中的 `dev:apps` 命令对所有项目进行启动

### 单独项目开发
- 运行根目录下 `package.json` 中的 `dev:packages` 命令对通用模块进行启动
- 运行所属项目 `package.json` 中的 `dev` 命令进行单个项目的启动

## 构建指南

- 运行根目录下 `package.json` 中的 `build` 命令对所有项目进行打包操作
