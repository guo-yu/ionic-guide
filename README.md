## ionic guide ![npm](https://badge.fury.io/js/ionic.png)

ionic 是使用 HTML5 及其他 Web 技术构建 hybrid app 的 Web 前端框架，旨在提升运行效率的同时依然能使用 Sass 与 Angular.js 构建优雅可维护的 hybrid App.
--- 

### 快速开始

现在就开始跟随这个基础教程学习，让我们在几分钟内使用 ionic 构建一个高质量的移动应用吧：

#### 安装 ionic

首先，确保你安装了 [Node.js](http://nodejs.org/)，然后，我们需要安装最新版的 Cordova 与 ionic 命令行工具。安装方法非常简单：

```
$ npm install -g cordova ionic
```
*提示：*: [Andorid](http://cordova.apache.org/docs/en/3.3.0/guide_platforms_android_index.md.html#Android%20Platform%20Guide) 与 [iOS](http://cordova.apache.org/docs/en/3.3.0/guide_platforms_ios_index.md.html#iOS%20Platform%20Guide) 平台各自有相应的依赖需要安装，请先查询上方的网址进行查询。

#### 创建 ionic 应用

开发者可以使用我们提供的应用框架进行创建，或者直接创建一个白板应用：

比如，使用 tabs 应用创建来创建一个应用，名为 myApp
```
$ ionic start myApp tabs 
```
tabs 应用效果如图：
![tabs app](http://ionicframework.com/img/getting-started/tabs-app.png)

相应的，创建一个边栏应用：
```
$ ionic start myApp sidemenu

边栏应用效果如图：
![menu app](http://ionicframework.com/img/getting-started/menu-app.png)
```
或者，创建一个白板应用：
```
$ ionic start myApp blank
```

#### 运行应用

我们可以非常方便的使用模拟器来运行 ionic 应用。由于 ionic 应用底层基于 Cordova 实现，我们只要借助于使用 Cordova 的调试工具即可启动应用，当然，ionic 命令行工具也提供了相应的功能：

以 iOS 应用来举例，现在我们在模拟器中启动 myApp 这个应用：

```
$ cd myApp
$ ionic platform add ios
$ ionic build ios
$ ionic emulate ios
```
稍等片刻，你应该能看到模拟器已经启动了。是不是非常简单？如果你觉得已经掌握了基本的操作，现在就可以开始研究范例应用代码，或者移步下一章节的文档了。

### ionic 组件文档

说到底，ionic 是一个 web 前端框架，也就是说，它由负责表现的样式模块，与负责交互的脚本文件组成，这些模块和文件共同协作完成功能，实现表现，再通过 Cordova 的封装，效果几乎与原生应用无异了。

#### 文档概览

欢迎，你读到了这里，看起来是要真心把这块骨头啃下去。我们知道 ionic 是一个前端框架，专注于表现层面，这以为这 ionic 所做的工作并不类似于 phonegap，而正好与之相反，ionic 的任务是专注于实现几乎和原生应用一样的 UI 甚至运行效率，而在这个层面与 Cordova 合作的天衣无缝。如果你还不确定是否理解 ionic 的定位，请先读一下这篇[文章](http://ionicframework.com/blog/where-does-the-ionic-framework-fit-in/)

ionic 目前依赖与 Angular.js，众所周知，这是一个 MVVM 框架，提供了数据与视图的动态双向绑定，用来构建可维护与复杂的 Web app。当然，在这之外，你也可以自由的选择其他的 UI 组件库或 MVC 框架，在未来，ionic 也会考虑支持其他的框架。

ionic 同时也会发布相关的 Cordova/PhoneGap 插件，以方便拓展 ionic 应用的更多可能性。

##### 下载 ionic

请移步[官方网站下载最新的稳定版本](http://ionicframework.com/docs/overview/#download)，请注意，最新版本的文档或接口可能与本中文文档的涵义不同，请以原文为准。

##### 命令行工具

我们的命令行工具基于 Node.js，开发者可以方便的使用命令行工具新建种子项目。当然，也可以选择直接 clone 种子[项目源码](https://github.com/driftyco/ionic-app-base)以新建项目。

种子项目默认包含相应的 CSS 与 Javascript 代码，也可选 Sass 源码、JS 框架相应插件，或者开源的免费 ionic icons.

#### CSS 模块
#### Javascript 接口文档
#### 概览

### 资源索引

* [ionic 官方网站](http://ionicframework.com/)
* [ionic @GitHub](https://github.com/driftyco/ionic)
* [ionic 应用案例](http://showcase.ionicframework.com/)

### MIT license
Copyright (c) 2014 turing &lt;o.u.turing@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the &quot;Software&quot;), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED &quot;AS IS&quot;, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

---
![docor](https://cdn1.iconfinder.com/data/icons/windows8_icons_iconpharm/26/doctor.png)
built upon love by [docor](https://github.com/turingou/docor.git) v0.1.3