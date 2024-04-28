_English | [简体中文](README.zh_CN.md)_
# TUICallEngine API Example Demo

## Introduction

This demo shows how to use the API of [tuicall-engine-webrtc](https://www.npmjs.com/package/tuicall-engine-webrtc) to build an audio and video calling application in a Vue2 project.

## Environment
Vue2.7 + vite + TypeScript

## Quick Start

1. Clone or download this repository

```
git clone https://github.com/tencentyun/TUICallKit.git
```

2. Navigate to the demo directory

```shell
cd ./RTC-CALL-ENGINE/Web/demo-vue2
```

3. Install dependencies

```shell
npm install
```

4. Modify SDKAppID and SecretKey
    - Refer to [the Service Activation](https://trtc.io/document/59832?platform=android&product=call) to obtain the `SDKAppID and SecretKey` for your application.
    - Open the `src/constants/call.ts` file and modify  `DefaultSdkAppId` to your application's `SDKAppID`, and `DefaultSecretKey` to your application's `SecretKey`.

5. Run the demo

```shell
npm run dev
```

## Start Your First Call
1. Open the running page, enter a userID (user_A) in the login box, click "Login". Then open the same address in another tab, enter user_B and log in.
2. Choose between 1v1 call or group call.
3. Enter user_B in the user ID input box and select audio call or video call in the media type.
4. `user_B` will receive a call, click "Answer" to start the call.

## 目录结构
```shell
.            
├── src/
│   ├── components/     # Common components and business components
│   ├── assets/         # Static assets
│   ├── constants/      # Constants
│   ├── hooks/          # Hooks, common logic
│   ├── router/         # Business router
│   ├── utils/          # Common utility methods
│   ├── stores/         # State management
│   ├── views/          # Pages
│   ├── main.ts         
│   └── App.vue
├── README.md
├── package.json
```
## Other Documents
- [TUICallEngine API](https://cloud.tencent.com/document/product/647/78757)
- [Quick Start with TUICallKit](https://cloud.tencent.com/document/product/647/78731)
- [TUICallKit (Web) FAQ](https://cloud.tencent.com/document/product/647/78769)