# Weex demo

> 这是一个基于 [Weex](https://weex.apache.org/cn/) 的练手项目，参考 [网易严选App感受 Weex 开发](https://segmentfault.com/a/1190000011027225) 并结合自身情况编写，目前处于起步阶段，很多东西还不熟悉，正在各种踩坑中，暂不建议对本项目进行查阅。

## Development Environment

* macOS 10.12.6
* Node `v8.6.0`
* Weex `v1.2.7`
* Xcode `v9.2`
* CocoaPods `v1.4.0`
* Android Studio `v3.0.1`

## Commands

### npm start

Starts the development server for you to preview your weex page on browser.
You can also scan the QR code using weex playground to preview weex page on native.

### npm run dev

Open the code compilation task in watch mode.

### npm run ios

(Mac only, requires Xcode)
Starts the development server and loads your app in an iOS simulator.

### npm run android

(Requires Android build tools)
Starts the development server and loads your app on a connected Android device or emulator.

### npm run pack:ios

(Mac only, requires Xcode)
Packaging ios project into ipa package.

### npm run pack:android

(Requires Android build tools)
Packaging android project into apk package.

### npm run pack:web

Packaging html5 project into `web/build` folder.

### npm run test

Starts the test runner.
