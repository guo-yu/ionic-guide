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
稍等片刻，你应该能看到模拟器已经启动了。

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