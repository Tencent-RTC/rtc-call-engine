<p align="center">
  <a href="https://trtc.io/">
    <img width="200" src="https://web.sdk.qcloud.com/trtc/webrtc/assets/trtc.io-logo.png">
  </a>
</p>

<h1 align="center" style="margin-top: -40px">TUICallEngine Web SDK</h1>

<div align="center">

An object-oriented TUICallEngine SDK library  

![NPM verison](https://img.shields.io/npm/v/tuicall-engine-webrtc) [![NPM downloads](https://img.shields.io/npm/dw/tuicall-engine-webrtc)](https://www.npmjs.com/package/tuicall-engine-webrtc) [![Typescript Supported](https://img.shields.io/badge/Typescript-Supported-blue)](https://www.npmjs.com/package/tuicall-engine-webrtc) [![Documents](https://img.shields.io/badge/-Documents-blue)](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html) 

</div>

<div align="center"> English | <a href="./README.zh_CN.md" target="_blank"> 简体中文</a> </div>


## Introduction
TUICallEngine Web SDK is based on [Tencent Cloud's IM](https://cloud.tencent.com/document/product/269/42440) and [Tencent Cloud's real-time communication](https://cloud.tencent.com/document/product/647/16788) solution. Supports audio and video calls in two-person and multi-person scenarios.

- [Online Demo](https://trtc.io/demo/homepage/#/detail?scene=callkit)
- [Changelog](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/tutorial-20-CHANGELOG.html)
- We offer SDKs for Web, Android, iOS, MiniProgram, Flutter, explore more in [trtc.io](https://trtc.io/products/call).


## Environment Supports
TUICallEngine Web SDK supports major modern browsers. For details, please refer to [Browsers Supported](https://web.sdk.qcloud.com/trtc/webrtc/v5/doc/en/tutorial-05-info-browser.html).

```text
Please be sure to use HTTPS protocol or localhost to deploy your Web App, otherwise a navigator.mediaDevices not found error will occur!
```

| [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Chrome | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/> Edge | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Firefox | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Safari | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>iOS Safari | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Opera |
| --------- | --------- | --------- | --------- | --------- | --------- |
| 56+ | 80+ | 56+ | 11+ | 11+ | 46+ |


## Install
npm:
```
$ npm install tuicall-engine-webrtc --save
```

yarn:
```
$ yarn add tuicall-engine-webrtc
```

Download manually：

1. download [tuicall-engine-webrtc.js](https://www.unpkg.com/tuicall-engine-webrtc@latest/tuicall-engine-webrtc.js).
2. copy `tuicall-engine-webrtc.js` to your project.


## Usage
Refer to the following two tutorials for a quick run-through of the demo and how to use the SDK to implement basic audio and video calling functionality.

- [Demo Quick Run](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/tutorial-00-%E5%AE%9E%E7%8E%B0%E5%8F%8C%E4%BA%BA%E9%80%9A%E8%AF%9D.html)
- [TUICallEngine Github Demo](https://github.com/mango2630/rtc-call-engine/tree/main/Web)

Explore SDK documents：[TUICallEngine Web SDK](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html)


## API Overview
- [TUICallEngine](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html) is the main entry for TUICallEngine SDK, providing APIs such as create tuiCallEngine instance [TUICallEngine.createInstance](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#.createInstance), [tuiCallEngine.login](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#login), [tuiCallEngine.call](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#call),  [tuiCallEngine.groupCall](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#groupCall).
- [tuiCallEngine](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html) instance, provides the core capability for real-time audio and video calls.
  - Start Call [call](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#call)
  - Accept call [accept](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#accept)
  - Reject call [reject](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#reject)
  - Hangup call [hangup](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#hangup)
  - Turn on camera [openCamera](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#openCamera)
  - Turn on microphone [openMicrophone](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#openMicrophone)
  - Turn off camera [closeCamera](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#closeCamera)
  - Turn off microphone [closeMicrophone](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#closeMicrophone)
  - Play remote video [startRemoteView](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#startRemoteView)
  - Stop playing remote video [stopRemoteView](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html#stopRemoteView)


## Directory
```
├── README-zh_CN.md
├── README.md
├── index.d.ts // ts declaration file
├── package.json
└── tuicall-engine-webrtc.js // sdk file base on ES modules
```
