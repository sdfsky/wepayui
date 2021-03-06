# WePayUI
<p>
<a href="https://www.npmjs.com/package/wepayui"><img src="https://img.shields.io/badge/npm-v0.0.1-blue.svg"></a>
<a href="https://github.com/wepayui/wepayui"><img src="https://img.shields.io/badge/github-wepayui-green.svg"></a>
</p>

## 简介
WePayUI 由微信支付为服务商和商户量身打造，用于快速制作符合微信支付规范的Web页面，提升开发效率。WePayUI 基于 <a href="https://github.com/weui/weui" target="_blank">WeUI</a> 拓展，包含基础组件和行业场景。

## 价值

<ul>
<li>快速实现自定义微信支付基础样式库</li>
<li>快速实现微信收款付款、收付款流程、收付款记录等支付相关HTML5页面</li>
<li>快速输出行业解决方案HTML5页面，如智慧停车场、智慧医院、智慧客运等</li>
</ul>

## 预览
PC端
<p>
    <a href="https://wepayui.github.io" target="_blank">https://wepayui.github.io</a>
</p>
移动端
<p>
<img width="250" height="250" src="https://wepayui.github.io/img/code.png">
</p>

## 快速使用
方式一：打开官网，按需复制代码或下载模板
<ul>
<li>PC端点击图标即可复制HTML代码，点击复制按钮可复制CSS代码。</li>
<li>使用 WePayUI 提供现成案例模板，可在场景找到对应的下载链接。</li>
</ul>
方式二：使用 CDN 资源
<pre>
&lt;!-- WePayUI 核心CSS 文件，压缩版 --&gt;
&lt;link rel=&quot;stylesheet&quot; href=&quot;https://act.weixin.qq.com/res/css/wepayui/0.0.1/wepayui.min.css&quot;&gt;

&lt;!-- WePayUI 核心CSS 文件，未压缩版，含less源码预览 --&gt;
&lt;link rel=&quot;stylesheet&quot; href=&quot;https://act.weixin.qq.com/res/css/wepayui/0.0.1/wepayui.css&quot;&gt;
</pre>

## 安装源码

我们提供了源码方便有一定开发能力的程序员使用，其中 WePayUI 安装包包含开发目录 src 和生产目录 dist ，其中开发环境包含Less、JavaScript、字体文件的源码，使用 gulp 作为编译系统。
### github下载
https://github.com/wepayui

### npm下载
<pre>
<code>$ npm install wepayui</code>
</pre>

## 定制

方式一：通过修改wepayui_config.json，把不需要使用的组件注释掉即可
<pre><code>[
    "weui-wepay-logo", 
    "weui-wepay-font", 
    "weui-wepay-flow", 
    "weui-icons", 
    "weui-dialog", 
    "weui-cell", 
    "weui-button", 
    "weui-actionsheet", 
    "weui-agree", 
    "weui-article", 
    "weui-flex", 
    "weui-footer", 
    "weui-grid", 
    "weui-loadmore", 
    "weui-mask", 
    "weui-media-box", 
    "weui-msg", 
    "weui-panel", 
    "weui-progress", 
    "weui-searchbar", 
    "weui-tab", 
    "weui-toast"
]</code></pre>

方式二：我们提供了<a href="https://github.com/wepayui/wepayui_build_tool" target="_blank">客户端构建工具<a>，你可以按需选择组件和场景自助构建。
<p>
    <img src="https://wepayui.github.io/img/wepayui_build.gif" alt="wepayui_build" class="wepayui-build-show">
</p>
## License

The MIT License(http://opensource.org/licenses/MIT)

请自由地享受和参与开源。
## 反馈

使用WePayUI过程有任何意见，请将你的感受和建议告诉我们。
<p>
    <a href="https://wj.qq.com/s/877757/a3ec" target="_blank">https://wj.qq.com/s/877757/a3ec</a>
</p>
