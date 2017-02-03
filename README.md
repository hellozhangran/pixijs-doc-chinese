Pixi.js — 一个JavaScript 2D渲染器
=============

![pixi.js logo](http://www.goodboydigital.com/pixijs/pixiV4_wide_full.jpg)




[![Inline docs](http://inch-ci.org/github/GoodBoyDigital/pixi.js.svg?branch=dev)](http://inch-ci.org/github/GoodBoyDigital/pixi.js)
[![Build Status](https://travis-ci.org/pixijs/pixi.js.svg?branch=dev)](https://travis-ci.org/pixijs/pixi.js)

此项目的目的是提供一个轻量级的跨平台的2D库，Pixi渲染器允许每个人都能享受硬件加速而不用知道先进的WebGL技术。当然，它是快的，的确很快

如果您想了解最新的pixi.js的消息，请关注我们的推特
([@doormat23](https://twitter.com/doormat23), [@rolnaaba](https://twitter.com/rolnaaba), [@bigtimebuddy](https://twitter.com/bigtimebuddy), [@ivanpopelyshev](https://twitter.com/ivanpopelyshev))
我们将会随时将消息告诉您！您也可以在我们的[我们的网站](http://www.goodboydigital.com/blog)上查阅资料，任何突破性的进展也会在那发布！

**您的支持帮助我们把Pixi.js做的更好，您可以在[Patreon](https://www.patreon.com/user?u=2384552&ty=h&u=2384552)上赞助，我们永远爱你**

### 用Pixi.js干什么以及什么时候用

Pixi.js是一个不用了解WebGL API或者处理浏览器兼容性就可以创建丰富的交互式图形，跨平台的应用和游戏的渲染器

Pixi.js拥有完整的[WebGL](https://en.wikipedia.org/wiki/WebGL)支持并且如狗有需要可以无缝降级到HTML5的[canvas](https://en.wikipedia.org/wiki/Canvas_element)。作为一个框架，Pixi.js是一个非常棒的工具去制作交互式的内容，*特别是近几年来Adobe Flash已经没落了*。用它制作你的图形丰富，交互性的网站、应用以及HTML5游戏。忘记跨平台和兼容性吧，优雅的降级意味着你做的更少，并且有更多乐趣。如果你想体验快速创建优雅的应用，不用考虑密密麻麻的底层代码，同时避免为了浏览器兼容问题而头疼，那就用Pixi.js做你的下一个项目吧。

**提高你的开发和发挥你的想象力**

### 学习 ###
- 网站: 在[官网](http://www.pixijs.com/)上查阅更多关于Pixi.js的内容。
- 开始: 查看@kittykatattack的综合[教程](https://github.com/kittykatattack/learningPixi)。
- 示例: Get stuck right in and play around with pixi code and features right [here](http://pixijs.github.io/examples/)!
- 示例: 立即开始并看看pixi的代码和新特性[在这里](http://pixijs.github.io/examples/)！
- 文档: 了解Pixi的API通过翻阅[文档](https://pixijs.github.io/docs/)
- Wiki: 其他各种各样的教程和资源请看[Wiki](https://github.com/pixijs/pixi.js/wiki/Resources).

### 社区 ###
- 论坛: [论坛](http://www.html5gamedevs.com/forum/15-pixijs/)和[StackOverflow](http://stackoverflow.com/search?q=pixi.js)都是你问问题的好地方。
- 灵感: 翻翻[画廊](http://www.pixijs.com/gallery)去寻找其他人制作的令人惊讶的东西
- 聊天: 你可以在[Gitter](https://gitter.im/pixijs/pixi.js)上加入我们去谈论关于Pixi。我们也有一个Slack频道。如果你想加入请给我发邮件(mat@goodboydigital.com)，我将会邀请你进入。


### 安装 ###

Pixi.js起步很容易！从这里可以得到预先构建好的版本：

发行分支 - 稳定版的Pixi.js
- 未压缩版: [http://pixijs.download/release/pixi.js]
- 压缩版: [http://pixijs.download/release/pixi.min.js]

开发分支 - 最前沿的Pixi.js版本
- Unminified: [http://pixijs.download/dev/pixi.js]
- Minified: [http://pixijs.download/dev/pixi.min.js]

另外，Pixi.js可以用Bower和npm安装，或者直接使用CDN嵌入至你的HTML中。

#### Bower 安装

```
$> bower install pixi.js
```

#### NPM 安装

```
$> npm install pixi.js
```

#### CDN 安装
通过cdnjs
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/pixi.js/4.2.2/pixi.min.js"></script>
```

通过bootcdn（译者添加，国内）
```html
<script src="https://cdn.bootcss.com/pixi.js/4.2.2/pixi.min.js"></script>
```

通过staticfile（译者添加，国内）
```html
<script src="https://cdn.staticfile.org/pixi.js/4.2.2/pixi.min.js"></script>
```

_注: `4.2.2` 可以换成任意[发行版](https://github.com/pixijs/pixi.js/releases)的版本号。_

### Demos ###

- [WebGL Filters!](http://www.goodboydigital.com/pixijs/examples/15/indexAll.html)
- [Run pixie run](http://www.goodboydigital.com/runpixierun)
- [Fight for Everyone](http://www.goodboydigital.com/casestudies/fightforeveryone)
- [Flash vs HTML](http://flashvhtml.com)
- [Bunny Demo](http://www.goodboydigital.com/pixijs/bunnymark)
- [Storm Brewing](http://www.goodboydigital.com/pixijs/storm)
- [Filters Demo](http://www.goodboydigital.com/pixijs/examples/15/indexAll.html)
- [Render Texture Demo](http://www.goodboydigital.com/pixijs/examples/11)
- [Primitives Demo](http://www.goodboydigital.com/pixijs/examples/13)
- [Masking Demo](http://www.goodboydigital.com/pixijs/examples/14)
- [Interaction Demo](http://www.goodboydigital.com/pixijs/examples/6)
- [photonstorm's Balls Demo](http://gametest.mobi/pixi/balls)
- [photonstorm's Morph Demo](http://gametest.mobi/pixi/morph)

感谢[@photonstorm](https://twitter.com/photonstorm)提供最后两个例子的并允许我们分享源代码 :)

### 贡献 ###

想要成为pixi.js项目的一部分？那太棒了！非常欢迎！无论你是发现Bug，需要新功能，还是你想从计划图中取得一份任务，请随意和我们取得联系

请在提交修改之前阅读[贡献指南](https://github.com/pixijs/pixi.js/blob/master/CONTRIBUTING.md)

### 当前特性 ###

- WebGL renderer (with automatic smart batching allowing for REALLY fast performance)
- Canvas renderer (Fastest in town!)
- Full scene graph
- Super easy to use API (similar to the flash display list API)
- Support for texture atlases
- Asset loader / sprite sheet loader
- Auto-detect which renderer should be used
- Full Mouse and Multi-touch Interaction
- Text
- BitmapFont text
- Multiline Text
- Render Texture
- Primitive Drawing
- Masking
- Filters
- [User Plugins](https://github.com/pixijs/pixi.js/wiki/Pixi-v3-Plugins)

### 基本用法示例 ###

```js
// and the root stage PIXI.Container.
// 应用首选创建WebGL渲染器
// 如果不支持则回退到canvas渲染
// 同时也会创建ticker和根容器PIXI.Container
var app = new PIXI.Application();

// 应用会创建一个canvas元素
// 因此你可以将它插入至DOM中
document.body.appendChild(app.view);

// 加载需要的图案
PIXI.loader.add('bunny', 'bunny.png').load(function(loader, resources) {

    // 创建了一个图案从bunny.png
    var bunny = new PIXI.Sprite(resources.bunny.texture);

    // 设置bunny的未知
    bunny.x = app.renderer.width / 2;
    bunny.y = app.renderer.height / 2;

    // 将旋转中心设为图案中央
    bunny.anchor.x = 0.5;
    bunny.anchor.y = 0.5;

    // 将bunny放入正在建造的场景中
    app.stage.addChild(bunny);
    
    // 监听帧更新
    app.ticker.add(function() {
         // 每一帧将bunny旋转一点点
        bunny.rotation += 0.01;
    });
});
```

### 如何构建 ###

请注意：对大多数用户来说都不需要构建此项目。如果你想使用pixi，只需下载我们[预先构建](https://github.com/pixijs/pixi.js/releases)的版本。你唯一需要构建此项目当你正在开发它的时候。

如果你没有Node.js和NPM，请先安装它们。然后在您Clone本仓库的文件夹用npm安装构建所需的依赖

```
$> npm install
```

然后就可以构建源码了，执行：

```
$> npm run dist
```

这条命令将会创建一个压缩版本在 `dist/pixi.min.js` 以及一个未压缩的版本在 `dist/pixi.js`通过pixi.js中的所有插件。

如果你不想要某个特定的插件，比如"interaction"或者"extras"，你可以不包含它们：

```
$> npm run dist -- --exclude extras --exclude interaction
```

你也可以使用简写形式 `-e`:

```
$> npm run dist -- -e extras -e interaction -e filters
```

### 如何生成文档 ###

文档可以用npm生成：

```
$> npm run docs
```

文档使用[Jaguar.js](https://github.com/davidshimjs/jaguarjs-jsdoc)和jsdoc格式，配置文件可以在[scripts/jsdoc.conf.json](scripts/jsdoc.conf.json)找到

### License ###

[MIT](http://opensource.org/licenses/MIT) License.

[![Analytics](https://ga-beacon.appspot.com/UA-39213431-2/pixi.js/index)](https://github.com/igrigorik/ga-beacon)
