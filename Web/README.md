_English | [简体中文](README.zh_CN.md)_
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
TUICallEngine Web SDK is based on [Tencent Cloud's IM](https://cloud.tencent.com/document/product/269/42440) and [Tencent Cloud's real-time communication](https://cloud.tencent.com/document/product/647/16788) solution.

- **Multi-platform interconnection**: We support various platforms such as Web, Android, iOS, Flutter, etc., as well as support cross-platform frameworks such as uni-app, we also plan to support MacOS, Windows and other devices.

- **Mobile terminal offline push**: We support offline wake-up on Android and iOS. When your app is offline, you can also receive call reminders in time. Currently, Google FCM, Apple, Xiaomi, Huawei, OPPO, VIVO, Meizu and other push services

- **Group (multi-person) calls**: We not only support 1-to-1 video calls, but also support multi-person video calls within a group, inviting group members to join in the middle, and support group members to actively join the call and more.

- **Multi-device login**: We also support the ability to log in to multiple devices on different platforms, your pad or mobile phone at the same time, for a larger screen and a more flexible experience.

- **More Features**: We also support multiple features such as custom ringtones, custom avatars, AI noise reduction, weak network optimization...


## Environment Supports
TUICallEngine Web SDK supports major modern browsers. For details, please refer to [Browsers Supported](https://web.sdk.qcloud.com/trtc/webrtc/v5/doc/en/tutorial-05-info-browser.html).

```text
Please be sure to use HTTPS protocol or localhost to deploy your Web App, otherwise a navigator.mediaDevices not found error will occur!
```

| [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Chrome | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/> Edge | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Firefox | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Safari | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>iOS Safari | [<img src="https://web.sdk.qcloud.com/trtc/webrtc/assets/logo/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Opera |
| --------- | --------- | --------- | --------- | --------- | --------- |
| 56+ | 80+ | 56+ | 11+ | 11+ | 46+ |

## Contents

**demo-vue2/**
- this directory contains the vue2 demo of TUICallEngine, which is integrated with all the features of the full TUICallEngine.

**demo-vue3/**
- this directory contains the vue3 demo of TUICallEngine, which is integrated with all the features of the full TUICallEngine.

## Have any questions?

- Welcome to submit [**issue**](https://github.com/tencentyun/TUICallKit/issues)
- Welcome to join our Telegram Group to communicate with our professional engineers! We are more than happy to hear from you，Click to join: https://t.me/+EPk6TMZEZMM5OGY1
