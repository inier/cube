<h1 align="center">cube</h1>

<div align="center">
<p align="center">中后台页面搭建低代码平台</p>
<img width="100%" alt="cube" src="https://user-images.githubusercontent.com/26452939/95151477-515a0700-07bd-11eb-96d4-8eb56f74c776.png">
</div>

## 🌍 地址

- [https://cube-pink.vercel.app/odin/editor](https://cube-pink.vercel.app/odin/editor)
- [https://blog.wipi.tech/odin/editor](https://blog.wipi.tech/odin/editor)

## ✨ 特性

- 💎 支持 `API` 接口交互
- 🎉 支持组件间交互
- ⚡️ 支持调整位置、大小，属性编辑

兼容性

`cube` 由于依赖了 React@16.8.0+ 提供的 Hooks 特性，因此只支持 React 16.8.0 及以上版本。

## 📦 思路

1. 通过 JSON 配置描述页面信息
2. 通过配置初始化 Store
3. 通过配置渲染页面
4. 通过交互组件修改 Store 数据，重新渲染页面

## ⌨️ 本地开发

```bash
# 克隆项目到本地
git clone git@github.com:fantasticit/cube.git

# 安装依赖
yarn

# 启动服务
yarn dev
```
