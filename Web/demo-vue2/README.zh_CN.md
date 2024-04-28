_[English](README.md) | 简体中文_
# TUICallEngine api example demo

## 简介

本 demo 演示了如何在 vue2 项目中使用 [tuicall-engine-webrtc](https://www.npmjs.com/package/tuicall-engine-webrtc) 的 API 搭建一套音视频通话应用。

## 环境
Vue2.7 + vite + TypeScript

## 快速跑通

1. 克隆或者直接下载此仓库源码

```
git clone https://github.com/tencentyun/TUICallKit.git
```

2. 进入 demo 目录

```shell
cd ./RTC-CALL-ENGINE/Web/demo-vue2
```

3. 安装依赖

```shell
npm install
```

4. 修改 SDKAppID、SecretKey
    - 参考 [开通服务](https://cloud.tencent.com/document/product/647/104662) 获取 `SDKAppID、SecretKey` .
    - 打开 `src/constants/call.ts` 文件，修改 `DefaultSdkAppId` 为应用的 `SDKAppID`，`DefaultSecretKey` 为应用的 `SecretKey`。

5. 运行 demo

```shell
npm run dev
```

## 开始您的第一次通话

1. 打开正在运行的页面，登录框中输入 userID (如 user_A)，点击登录，再打开同样地址的页面，输入 user_B 并登录。
2. 选择单人通话或者群组通话。
3. 用户 id 输入框内输入 user_B，并可在媒体类型选择音频通话或者视频通话。
4. `user_B` 会收到来电，点击接听即可开始通话。

## 目录结构
```shell
.            
├── src/
│   ├── components/     # 公共组件和业务组件
│   ├── assets/         # 静态资源存放
│   ├── constants/      # 常量
│   ├── hooks/          # Hook 相关，公共逻辑
│   ├── router/         # 业务路由
│   ├── utils/          # 公共工具方法
│   ├── stores/         # 状态管理相关
│   ├── views/          # 存放页面
│   ├── main.ts         
│   └── App.vue
├── README.md
├── package.json
```
## 其他文档
- [TUICallEngine API](https://cloud.tencent.com/document/product/647/78757)
- [TUICallKit 快速接入](https://cloud.tencent.com/document/product/647/78731)
- [TUICallKit (Web) 常见问题](https://cloud.tencent.com/document/product/647/78769)