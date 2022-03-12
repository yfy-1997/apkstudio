<h1 align="center">
  <a href="http://www.vaibhavpandey.com/apkstudio/">
    <img src="https://raw.githubusercontent.com/vaibhavpandeyvpz/apkstudio/master/resources/icon.png" alt="APK Studio" height="192px">
  </a>
  <br>
  APK Studio
</h1>

基于开源、跨平台[Qt](https://www.Qt.io/)的 IDE，用于逆向工程[Android](https://Android.com/)应用程序包。它具有一个友好的类 ide 的布局，包括代码编辑器和语法突显支持 \*.Smali 代码文件。

[![Screenshot](https://raw.githubusercontent.com/vaibhavpandeyvpz/apkstudio/master/resources/screenshot.png)](https://raw.githubusercontent.com/vaibhavpandeyvpz/apkstudio/master/resources/screenshot.png)

<p align="center">
  <a href="https://ci.appveyor.com/project/vaibhavpandeyvpz/apkstudio">
    <img src="https://img.shields.io/appveyor/ci/vaibhavpandeyvpz/apkstudio.svg" alt="AppVeyor">
  </a>
  <a href="https://travis-ci.org/vaibhavpandeyvpz/apkstudio">
    <img src="https://img.shields.io/travis/vaibhavpandeyvpz/apkstudio.svg" alt="Travis CI">
  </a>
  <a href="https://github.com/vaibhavpandeyvpz/apkstudio/releases/latest">
    <img src="https://img.shields.io/github/release/vaibhavpandeyvpz/apkstudio.svg" alt="Release">
  </a>
  <a href="https://github.com/vaibhavpandeyvpz/apkstudio/releases">
    <img src="https://img.shields.io/github/downloads/vaibhavpandeyvpz/apkstudio/total.svg" alt="Downloads">
  </a>
</p>

<h3 align="center">Sponsor</h3>
<p align="center">
  <a href="https://appfrom.site/">
    <img src="https://appfrom.site/external/images/ad-banner-450x128.png" alt="appfrom.site">
  </a>
</p>

如果你只是想快速反编译一个 Android 应用程序，你可以使用[DeAPK-Online APK 反编译器](https://DeAPK.vaibhavpandey.com/)，它可以让你使用[apktool](https://github.com/ibotpeaches/apktool)和[jadx](https://github.com/skylot/jadx)反编译一个 Android 应用程序。

### 功能特色
- 跨平台， 运行在 **Linux**, **Mac OS X** & **Windows**
- 反编译/重新编译/签名 & 安装 APKs
- 内置代码编辑器 (\*.java; \*.smali; \*.xml; \*.yml) w/ 支持代码高亮
- 用于图像 (\*.gif; \*.jpg; \*.jpeg; \*.png) 文件浏览器
- 内置的十六进制编辑二进制文件

### 下载
请前往 [下载页](https://github.com/vaibhavpandeyvpz/apkstudio/Releases) 下载。重要提示: 确保 `JAVA home` 环境变量指向一个有效的 jdk环境，以便 jadx 能够运行。

### 构建
来源于构建的信息可以在[Wiki](https://github.com/vaibhavpandeyvpz/apkstudio/Wiki)中找到。

### 致谢
- [iBotPeaches](https://github.com/iBotPeaches) for [apktool](https://ibotpeaches.github.io/Apktool)
- [patrickfav](https://github.com/patrickfav) for [uber-apk-signer](https://github.com/patrickfav/uber-apk-signer)
- [skylot](https://github.com/skylot) for [jadx](https://github.com/skylot/jadx)
- [probonopd](https://github.com/probonopd) for [linuxdeployqt](https://github.com/probonopd/linuxdeployqt)
- [Jürgen Skrotzky](https://github.com/Jorgen-VikingGod) for [Qt-Frameless-Window-DarkStyle](https://github.com/Jorgen-VikingGod/Qt-Frameless-Window-DarkStyle)
- [Antonio Davide](https://github.com/Dax89) for [QHexView](https://github.com/Dax89/QHexView)
- [p.yusukekamiyamane](https://p.yusukekamiyamane.com/) for [Fugue](https://p.yusukekamiyamane.com/) icons
- [Icons8](https://icons8.com/) for various icons
- [Surendrajat](https://github.com/Surendrajat) for maintaining project while I couldn't

**注意**: 如果遇到任何问题，请确保选中IDE底部的 **控制台** 输出，以获取程序实际执行的命令的输出。报告与APK Studio有关的任何问题请在Github上[此处](https://github.com/vaibhavpandeyvpz/apkstudio/issues)。请注意，[apktool]有一个问题(http://ibotpeaches.github.io/Apktool/)不是**APK Studio**的问题。请在开票前核实问题的背景。

---

##### 免责声明
与[apktool](http://ibotpeaches.github.io/apktool/)相同，如果您对于 **APK Studio** 的使用，既不打算用于盗版，也不打算用于其他非法用途，那么可以用于本地化，添加一些功能或支持自定义平台，分析应用程序等等。
