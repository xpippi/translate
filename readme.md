
# Immersive Translate - 沉浸式翻译扩展

Let's experience immersive web translation, with Google and Yandex under the hood, with support for both firefox and chrome 

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/immersive-translate/immersive-translate?label=latest%20version&sort=semver)](https://github.com/immersive-translate/releases)
[![GitHub release date](https://img.shields.io/github/release-date/immersive-translate/immersive-translate?labely)](https://github.com/immersive-translate/immersive-translate/latest)
[![GitHub issues](https://img.shields.io/github/issues/immersive-translate/immersive-translate?color=red)](https://github.com/immersive-translate/immersive-translate/issues)
[![GitHub license](https://img.shields.io/github/license/immersive-translate/immersive-translate?color=lightgrey)](https://github.com/immersive-translate/immersive-translate/blob/master/LICENSE)


说明： 该扩展Fork自[TWP](https://github.com/FilipePS/Traduzir-paginas-web)插件，我为其添加了以下功能：

- 双语显示，按照段落分割
- 只翻译网页里的内容区域，这极大的增强了翻译的阅读体验，而不是像之前那样网页的所有元素都被翻译，类似浏览器的阅读模式，所以该插件被重新命名为“沉浸式翻译”
- 为常用网站做了定制优化，比如推特，Reddit，Hacker News等，我希望这个插件足够通用，不需要为绝大多数网站做定制，但是往往有一些网站由于不规范，或者非内容类网站，这些网站在单独优化后体验更好，所以我们会对这类网站做单独适配，同时坏处就是可能随时网站的更新而失效，所以这里我会持续优化。如果有常用的网站翻译显示不佳，欢迎在[Isuee](https://github.com/theowenyoung/Traduzir-paginas-web/issues)或[Telegram群组](https://t.me/+rq848Z09nehlOTgx)中提出。
- 支持PDF文件双语对照翻译
- 配合epub在线阅读网站<https://1paragraph.app/> 即可实现双语阅读国外电子书

沉浸式翻译和[原插件](https://github.com/FilipePS/Traduzir-paginas-web)的目标不太一样，原插件更多的是作为一个非常好用的通用翻译扩展，是浏览器自带翻译的良好替代品，在没有浏览器自带翻译的浏览器里提供了巨大的帮助。但是本插件更关注经常需要看外文的用户在阅读外文页面时能有一个良好的体验（我想做这个插件就是因为我经常需要在[Buzzing](https://www.buzzing.cc/)上浏览大量的外媒文章），所以该插件的目标群体是：

- 经常阅读国外长篇文章，论文
- 阅读外文PDF，外语电子书
- 希望快速浏览推特，Reddit，Hacker News，Github Issue等国外论坛网站
- 希望同时显示双语来学习目标语言
- 希望同时显示双语，以平衡部分机器翻译的不知所云
- 希望尽快摆脱这个扩展，直接习惯看原文的用户的过度助手

该扩展同时支持（依赖）谷歌翻译引擎或Yandex翻译引擎，同时支持使用Bing，Deepl进行文本选中翻译，插件完全免费，希望我们都能尽可能平等的获取知识，不要让语言成为障碍，感谢[原作者](https://github.com/FilipePS/Traduzir-paginas-web)为这个项目付出的巨大努力。

## 安装说明

### Firefox 

已发布到商店，可以[直接下载](https://addons.mozilla.org/en-US/firefox/addon/immersive-translate/)。如果你想最快体验到新版，也可以直接在[Release页面](https://github.com/theowenyoung/Traduzir-paginas-web/releases)下载最新构建的版本，已签名，可以直接安装。



### Chrome/Edge

chrome,edge商店的升级和发布正在进行中，目前需要手动安装：

1. 在[这里](https://github.com/theowenyoung/Traduzir-paginas-web/releases)下载chrome的压缩包
2. 解压到一个以后不会删除的文件夹
3. 打开扩展管理窗口，`chrome://extensions`
4. 激活开发者模式
5. 载入刚解压的扩展文件夹
6. 安装后，target语言可以选中文
7. 接下来可以设置为always自动翻译英文，或者右键手动点击翻译本页面，即可有双语显示，打开推特试试看！

## 项目状态

目前依然处于Alpha阶段，但是常用内容网站在使用上已经没有问题，同时在[Telegram 沉浸式插件讨论组](https://t.me/+rq848Z09nehlOTgx)中经常得到很多有用的反馈，如果你有反馈，也可以在[群里](https://t.me/+rq848Z09nehlOTgx)提出。

在[Release页面](https://github.com/theowenyoung/Traduzir-paginas-web/releases)会有一个nightly版本被频繁的构建，建议喜欢体验最新版/或者想帮忙测试的同学，可以手动安装nightly版本，firefox的扩展包已签名，可以直接下载后作为扩展文件安装。

> 现在还没有任何选项可以设置,欢迎加入一起开发呀～

## 截图

### Twitter

![twitter](assets/twitter.png)

### Reddit

![reddit](assets/reddit.png)

### PDF文件

![pdf](assets/pdf.png)


### Epub文件

![epub](assets/epub.jpg)

> 配合epub在线阅读网站<https://1paragraph.app/> 即可实现如图的通过双语阅读国外电子书


### Hacker News

![hackernews](assets/hn-details.png)



---

## Install

#### Firefox
- Desktop users, download from [Mozilla Addons](https://addons.mozilla.org/en-US/firefox/addon/immersive-translate/).
- Mobile users, see [this tutorial](https://www.ghacks.net/2020/10/01/you-can-now-install-any-add-on-in-firefox-nightly-for-android-but-it-is-complicated/).

#### Chromium based browsers

1. Download [the latest release chrome file](https://github.com/immersive-translate/immersive-translate/releases/)
2. Extract the zip file
3. Open your browser's extension manager
4. Activate developer mode
5. Load the extension with the option "Load unpacked"

This extension Forks from the [TWP](https://github.com/FilipePS/Traduzir-paginas-web) plugin, to which I have added the following features.

- Bilingual display, split by paragraph
- Translation of only the content area of the page, which greatly enhances the reading experience of the translation, instead of the previous one where all elements of the page are translated, similar to the browser reading mode, so the plugin was renamed "Immersive Translation"
- I hope this plugin is universal enough that it does not need to be customized for most websites, but there are often some websites that are not standardized, or non-content websites, and these websites are better after separate optimization, so we will do separate adaptations for such websites, and the downside is that the website may not work at any time. The bad thing is that the website may fail at any time with the update of the website, so here I will continue to optimize. If you have a commonly used website that does not translate well, please feel free to ask in [Isuee](https://github.com/theowenyoung/Traduzir-paginas-web/issues) or [Telegram group](https://t.me/+rq848Z09nehlOTgx ).
- Support bilingual translation of PDF files
- Cooperate with epub online reading website <https://1paragraph.app/> to realize bilingual reading of foreign e-books

Immersive translation is not quite the same as the goal of [original plugin](https://github.com/FilipePS/Traduzir-paginas-web), the original plugin is more as a very good general translation extension, a good alternative to browser-built translation, and a great help in browsers without browser-built translation . But this plugin is more concerned about users who often need to read foreign languages to have a good experience when reading foreign language pages (I want to do this plugin because I often need to browse a lot of foreign media articles on [Buzzing](https://www.buzzing.cc/)), so the target group of this plugin is

- often read long articles, papers from abroad
- Read foreign language PDF, foreign language e-books
- want to quickly browse Twitter, Reddit, Hacker News, Github Issue and other foreign forum sites
- Want to display both languages to learn the target language
- I hope to display bilingualism at the same time to balance the unknowingness of some machine translation
- I hope to get rid of this extension as soon as possible, which is an excessive assistant for users who are directly used to reading the original language

The extension also supports (relies on) Google translation engine or Yandex translation engine, while supporting the use of Bing, Deepl for text selection translation, the plug-in is completely free, I hope we can all get knowledge as equally as possible, thanks to [original author](https://github.com/FilipePS/Traduzir-paginas-web) for the great effort he put into this project.


## Screenshots
| Menu 1 | Menu 2 | Translated |
| :--: | :--: | :--: |
| <img src="https://addons.mozilla.org/user-media/previews/full/258/258434.png" height="200"> | <img src="https://addons.mozilla.org/user-media/previews/full/258/258435.png" height="200"> | <img src="https://addons.mozilla.org/user-media/previews/full/258/258436.png" height="200"> |


## FAQ

**Why do you need to access your data on all the websites you visit?**

To translate any website it is necessary to access and modify the text of the web pages. And the extension can only do that, with that permission.

**How are the pages translated?**

The pages are translated using the Google or Yandex translation engine (you choose).

**And how's my privacy?**

[Privacy policy](https://addons.mozilla.org/addon/traduzir-paginas-web/privacy/): We do not collect any information. However, to translate, the contents of the web pages will be sent to Google or Yandex servers.

**Limitations**

Some pages like [support.mozilla.org](https://support.mozilla.org/) and [addons.mozilla.org](http://addons.mozilla.org/) will not be translated. For security reasons, the browser blocks extensions from accessing these sites.

## Todo


- [ ] - adapt for Github
- [ ] - backup默认文件名还是TWP
- [ ] - option页面从extension中打开的显示问题 
- [ ] - 版本号自动添加
- [ ] - youtube comments
- [ ] - better for github

