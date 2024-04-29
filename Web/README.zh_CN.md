<p align="center">
  <a href="https://trtc.io/">
    <img width="200" src="https://web.sdk.qcloud.com/trtc/webrtc/assets/trtc.io-logo.png">
  </a>
</p>

<h1 align="center" style="margin-top: -40px">TUICallEngine Web SDK</h1>

<div align="center">

![NPM verison](https://img.shields.io/npm/v/tuicall-engine-webrtc) [![NPM downloads](https://img.shields.io/npm/dw/tuicall-engine-webrtc)](https://www.npmjs.com/package/tuicall-engine-webrtc) [![Typescript Supported](https://img.shields.io/badge/Typescript-Supported-blue)](https://www.npmjs.com/package/tuicall-engine-webrtc) [![Documents](https://img.shields.io/badge/-Documents-blue)](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html)

</div>

<div align="center"> 简体中文 | <a href="./README.md" target="_blank"> English </a> </div>


## 简介
TUICallEngine 是基于腾讯云 [即时通信 IM](https://cloud.tencent.com/document/product/269/42440) 和 [实时音视频 TRTC](https://cloud.tencent.com/document/product/647/16788) 两项付费 PaaS 服务构建出的音视频通信 SDK，支持双人和多人场景下的音视频通话。

- [在线 Demo](https://rtcube.cloud.tencent.com/prerelease/component/experience-center/index.html#/detail?scene=callkit)
- [更新日志](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/tutorial-20-CHANGELOG.html)
- 我们提供适用于 Web、Android、iOS、小程序、Flutter 的 SDK，更多信息请参见 [trtc.io](https://cloud.tencent.com/document/product/647/78742)。


## 环境支持
TUICallEngine Web SDK 支持市面上主流浏览器，详情参考：[浏览器支持情况](https://web.sdk.qcloud.com/trtc/webrtc/v5/doc/zh-cn/tutorial-05-info-browser.html)。

```text
请务必使用 HTTPS 协议或者 localhost 来部署您的 Web App，否则会出现找不到 navigator.mediaDevices 错误！
```

| [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Chrome | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/> Edge | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Firefox | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Safari | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>iOS Safari | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Opera |
| --------- | --------- | --------- | --------- | --------- | --------- |
| 56+ | 80+ | 56+ | 11+ | 11+ | 46+ |


## 安装
使用 npm:
```
$ npm install tuicall-engine-webrtc --save
```

使用 yarn:
```
$ yarn add tuicall-engine-webrtc
```

手动下载 sdk 包：
1. 下载 [tuicall-engine-webrtc.js](https://www.unpkg.com/tuicall-engine-webrtc@latest/tuicall-engine-webrtc.js)。
2. 将 `tuicall-engine-webrtc.js` 复制到你的项目中。


## 使用
参考下述两个教程，可快速跑通 Demo 及了解如何使用 SDK 实现基础音视频通话功能。

- [实现双人通话](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/tutorial-00-%E5%AE%9E%E7%8E%B0%E5%8F%8C%E4%BA%BA%E9%80%9A%E8%AF%9D.html)
- [TUICallEngine Github Demo](https://github.com/mango2630/rtc-call-engine/tree/main/Web)

TUICallEngine API 文档详见：[TUICallEngine Web SDK](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html)。


## API 概要
- [TUICallEngine](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html) 是整个 SDK 的主入口，提供创建 tuiCallEngine 对象 [TUICallEngine.createInstance](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#.createInstance)。登录 [tuiCallEngine.login](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#login)。发起 1v1 通话 [tuiCallEngine.call](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#call)。发起群组通话 [tuiCallEngine.groupCall](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#groupCall)。
- [tuiCallEngine](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html) 对象，提供实时音视频通话的核心能力。
  - 开始 1v1 通话 [call](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#call)
  - 接通 [accept](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#accept)
  - 拒绝 [reject](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#reject)
  - 挂断 [hangup](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#hangup)
  - 打开摄像头 [openCamera](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#openCamera)
  - 打开麦克风 [openMicrophone](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#openMicrophone)
  - 关闭摄像头 [closeCamera](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#closeCamera)
  - 关闭麦克风 [closeMicrophone](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#closeMicrophone)
  - 播放远端视频 [startRemoteView](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#startRemoteView)
  - 停止播放远端视频 [stopRemoteView](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/zh-cn/TUICallEngine.html#stopRemoteView)


## 目录结构
```
├── README-zh_CN.md
├── README.md
├── index.d.ts // 类型声明文件
├── package.json
└── tuicall-engine-webrtc.js // 基于 es 模块的 sdk 包
```
