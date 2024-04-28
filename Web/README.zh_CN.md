_[English](README.md) | 简体中文_
<p align="center">
  <a href="https://trtc.io/">
    <img width="200" src="https://web.sdk.qcloud.com/trtc/webrtc/assets/trtc.io-logo.png">
  </a>
</p>

<h1 align="center" style="margin-top: -40px">TUICallEngine Web SDK</h1>

<div align="center">

![NPM verison](https://img.shields.io/npm/v/tuicall-engine-webrtc) [![NPM downloads](https://img.shields.io/npm/dw/tuicall-engine-webrtc)](https://www.npmjs.com/package/tuicall-engine-webrtc) [![Typescript Supported](https://img.shields.io/badge/Typescript-Supported-blue)](https://www.npmjs.com/package/tuicall-engine-webrtc) [![Documents](https://img.shields.io/badge/-Documents-blue)](https://web.sdk.qcloud.com/component/trtccalling/doc/TUICallEngine/web/en/TUICallEngine.html) 
</div>

## Introduction
TUICallEngine Web SDK是基于腾讯云的 [即时通信 IM](https://cloud.tencent.com/document/product/269/42440) 和 [实时音视频 TRTC](https://cloud.tencent.com/document/product/647/16788) 解决方案开发的。

- **多平台互联互通**：我们支持Web、Android、iOS、 Flutter、微信小程序等各个平台，同时也支持类似uni-app等跨平台框架，未来我们还计划支持、MacOS、Windows等设备。
- **移动端离线推送**：我们支持Android、iOS 的离线唤醒，当您的应用处于离线状态时，也可以及时收到来电提醒，目前已经支持Google FCM、Apple、小米、华为、OPPO、VIVO、魅族等多个推送服务
- **群组（多人）通话**：我们不仅仅支持1对1的视频通话，还支持在群组内发起多人视频通话，支持中途邀请群成员加入，支持群成员主动加入通话等。
- **多设备登录**：我们也支持您可以在不同平台上登录多台设备，您可以同时在您的Pad、手机登录，更大屏幕，体验更好跟更灵活。
- **更多特性**：我们也支持自定义铃音、自定义头像、AI降噪、弱网优化等多个Feature...


## Environment Supports
TUICallEngine Web SDK supports major modern browsers. For details, please refer to [Browsers Supported](https://web.sdk.qcloud.com/trtc/webrtc/v5/doc/en/tutorial-05-info-browser.html).

```text
Please be sure to use HTTPS protocol or localhost to deploy your Web App, otherwise a navigator.mediaDevices not found error will occur!
```

| [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Chrome | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/> Edge | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Firefox | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Safari | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>iOS Safari | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Opera |
| --------- | --------- | --------- | --------- | --------- | --------- |
| 56+ | 80+ | 56+ | 11+ | 11+ | 46+ |

## Contents

**call-engine-demo-vue2/**
- 这个目录包含了 TUICallEngine 的 Vue2 演示，集成了完整的TUICallEngine的所有功能。

**call-engine-demo-vue3/**
- 这个目录包含了 TUICallEngine 的 Vue3 演示，集成了完整的TUICallEngine的所有功能。

## Have any questions?

- 如果您在使用过程中有遇到什么问题，欢迎提交 [**issue**](https://github.com/Tencent-RTC/rtc-call-engine/issues)。
- 了解更多详情，请到 [腾讯云通信官方社群](https://zhiliao.qq.com) 进行咨询和反馈。