# site-status

一个基于 UptimeRobot API 的在线状态面板

![IMSYY-站点监测.png](https://github.com/mao888/site-status/assets/59285170/71bc0bb3-aa05-48e9-b6d3-1a9e75654c62)

## 特色

- 站点状态总览
- 流畅的动画
- 数据获取失败提醒
- 移动端适配

## 事先准备

- 您需要先到 [UptimeRobot](https://uptimerobot.com/dashboard) 添加站点监控，并在 `My Settings` 页面获取 类型为 `Read-Only API Key` 的 `API Key`

## 如何使用

- `star` 并 `fork` 😘
- 按照下方部署操作来安装依赖
- 在 `.env` 文件中进行配置修改
- 将打包后的文件上传至网站空间或者直接使用 `Vercel` 或者 `Cloudflare` 直接部署该项目

## 部署

### 安装依赖
requires at least Node.js v18.12
```shell
nvm install 20
```
若没有 pnpm
```shell
npm install pnpm -g
```
安装依赖
```shell
pnpm install
```

### 开发
```bash
pnpm dev
```

### 打包
```bash
pnpm build
```

## 鸣谢

 - [uptime-status](https://github.com/yb/uptime-status) 基于此项目进行修改
