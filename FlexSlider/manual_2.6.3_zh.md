[![Gitter chat](https://badges.gitter.im/woothemes/FlexSlider.png)](https://gitter.im/woothemes/FlexSlider)

# FlexSlider 2.6.3
http://www.woothemes.com/flexslider/ - Copyright (c) 2015 WooThemes

## Releases git仓库 

The `master` branch of this repository is always the latest development version of FlexSlider. Please view the [Releases](https://github.com/woothemes/FlexSlider/releases) section for a list of official FlexSlider builds.  
'master'分支是FlexSlider的git仓库的最新开发版本。请浏览FlexSlider官方[git仓库](https://github.com/woothemes/FlexSlider/releases)

### Contributing 投稿

We encourage contributions to FlexSlider and will review all pull requests submitted.  
我们支持开发者对FlexSlider做出投稿并将审查所有的请求提交。  

Before contributing, please see our [Contributing Guide](https://github.com/woothemes/FlexSlider/blob/master/CONTRIBUTING.md).  
在投稿之前，请阅读我们的[投稿向导](https://github.com/woothemes/FlexSlider/blob/master/CONTRIBUTING.md).  

### Roadmap 路线图

To keep up to date with how FlexSlider's development roadmap looks, please see our [development roadmap](https://github.com/woothemes/FlexSlider/wiki/Roadmap).
为了理解FlexSlider的开发路线图，请阅读我们的[开发路线图](https://github.com/woothemes/FlexSlider/wiki/Roadmap)  

## Updates 更新

** Version 2.6.3 **  

** Rollback fade fixes, due to harsh fade reports. **  
** 根据严重的渐变错误报告修复淡入回退错误。**  

** Version 2.6.2 **  

** Minor update to fix issues with varying heights and overflow onto content below the slider. Fixes the visibility of the pagination and the navigation in the "fade" mode. **  
** 小更新以解决不同高度的适应性和内容溢出到滑块下面的问题。修复分页的可见性和“渐变”模式的导航条**  

** Version 2.6.1 **  

** SmoothHeight now uses innerHeight() instead of height() to account for padding in calculation. Defining var altText to prevent error. bower.json add fonts folder on main field. Changed true to false in order to make sure whether or not to allow a slider comprised of a single slide. **  
** 现在SmoothHeight使用innerHeight()代替height()计算calculation中的padding。定义变量altText阻止错误。bower.json的主域增加字体文件夹。将true修改为false以便确保单个滑块允许构成幻灯(次句很没把握)。**  

** Version 2.6.0 **

** Adds composer json file, scope fix for focused keyword, fixes bower demo folder exclusion, z-index fix for disabled nav arrow, play/pause accessibility fix, itemMargin fix for slider items, fixes accessibility for in focus elements and pagination controls, firefox fix for text selection on slider carousel, adds data-thumb-alt image alt attribute. **  
** 增加composer.json文件，集中关键字的修复(次句很没把握)，修复bower demo文件夹的排除，z-index修复导航箭头不可用，播放/暂停易用性修复，itemMargin修复滑块组，元素获得焦点和分页控件的易用性修复，修复firefox旋转滑块文本选择，添加data-thumb-alt图片alt属性。**  

** Version 2.5.0 **  

** Bumped compatibility support starting with jQuery 1.7+. pausePlay icon fix. Firefox touch event fix. Adds customDirectionNav param. **  
** 兼容性支持修改为jQuery 1.7+。pausePlay图标修复。Firefox触摸时间修复。增加customDirectionNav参数。**  

** Version 2.4.0 **  

** Update for improved standards. Adds classes to li nav elements. Reset for li elements in stylesheet. **  
** 更新以提高标准。增加li导航元素的类。 重置li元素样式。**  

** Version 2.3.0 **  

** Fixes pauseInvisible attribute issue with Chrome and the Page Visibility API. **  
** 修复Chrome中pauseInvisible属性问题和页面可见性API **  

** Version 2.2.2 **  

** Fixes minified JavaScript file to remove merge conflicts. **  
** 修复min JavaScript文件删除合并冲突。 **  

** Version 2.2.0 **  

- Fixed event handler conflicts with devices that are both click and touch enabled. e.g., Windows 8.  
- 修复事件处理程序与同时单击和触摸启用的设备发生冲突。例如，Windows 8。  
- Made all slider variables public, stored in `slider.vars`. This allows manipulation of `slider.vars.minItems` and `slider.vars.maxItems` on the fly to create different fluid grids at certain breakpoints. [Check out this example demonstrating a basic technique](http://flexslider.woothemes.com/dynamic-carousel-min-max.html)  
- 把所有滑块变量修改为public，存储在`slider.vars`。这允许控制`slider.vars.minItems `和`slider.vars.maxItems`在某些断点创建不同的流体网格。[看看这个基础例子展示基本技术](http://flexslider.woothemes.com/dynamic-carousel-min-max.html)  
- Fixed calculations that were causing strange issues with paging and certain FlexSliders to move out of alignment.  
- 修复计算造成的奇怪分页问题和FlexSliders移出对齐。  

*Be sure to test v2.2.0 with your current slider, before pushing live, to ensure everything is playing nicely.*  
*在开始之前，务必测试v2.2.0确保运行正常。  

-----
## Geeral Notes Geeral笔记
FlexSlider is no longer licensed under the MIT license. FlexSlider now uses the license, GPLv2 and later.  
FlexSlider不再遵循MIT许可协议。FlexSlider现在遵循GPLv2及其更新版本。  

In an effort to move the plugin forward, support for jQuery 1.4.2 has been dropped. The plugin now requires jQuery 1.7.0+. If you don't have access to the later versions of jQuery, [FlexSlider 1.8](https://github.com/woothemes/FlexSlider/tree/flexslider1) should be a perfectly suitable substitute for your needs!  
为了支持插件的成长，放弃了对jQuery 1.4.2的支持。现在插件需要jQuery 1.7.0+。如果你不使用较高版本的jQuery,[FlexSlider 1.8](https://github.com/woothemes/FlexSlider/tree/flexslider1)应该能满足你的需要。  


Your old styles and properties *might not work out of the box*. Some property names have been changed, noted below, as well as namespacing prefixes being applied to all elements. This means that `.flex-direction-nav .next` is now `.flex-direction-nav .flex-next` by default. The namespacing property is exposed, free for you to change.
你的原有样式和属性 *可能失效*。一些属性名称已经修改，需要注意命名空间前缀被应用到所有的元素。这意味着现在是`.flex-direction-nav .next`。默认是`.flex-direction-nav .flex-next`。命名空间属性是开放的，你可以自由改动。  

No more overflow hidden woes! The plugin now generates a viewport element to handle the tedious task of working around overflow hidden. Yay!  
不再有溢出隐藏的痛苦，插件现在生成一个视窗元素来处理环绕隐藏的繁琐操作。耶！  

The slider element is now accessible outside of the callback API via the jQuery .data() method. Example use: `$('#slider').data('flexslider')`  
滑块元素现在可以通过jQuery的.data()方法快速实现回调API。例如:`$('#slider').data('flexslider')`  

Helper strings have been added for performing actions quickly on FlexSlider elements. Example uses:  
为了FlexSlider快速执行操作添加了辅助代码。例如：  

- `$('#slider').flexslider("play")  //Play slideshow`	播放幻灯片  
- `$('#slider').flexslider("pause") //Pause slideshow`  暂停幻灯片  
- `$('#slider').flexslider("stop") //Stop slideshow`    停止幻灯片  
- `$('#slider').flexslider("next")  //Go to next slide`  下一个幻灯片  
- `$('#slider').flexslider("prev")  //Go to previous slide`  上一个幻灯片  
- `$('#slider').flexslider(3)       //Go fourth slide`		 到第四个（指定的）幻灯片  

Two new methods are available for adding/removing slides, `slider.addSlide()` and `slider.removeSlide()`. More details about this coming soon.  
为了增加/移出幻灯片增加了两个方法，`slider.addSlide()`和`slider.removeSlide()`。更多相关细节：  

- `slider.addSlide(obj, pos)` accepts two parameters, a string/jQuery object and an index.  
- `slider.addSlide(obj,pos)` 有2个参数，一个string/jQuery对象和一个索引。  
- `slider.removeSlide(obj)` accepts one parameter, either an object to be removed, or an index.  
- `slider.removeSlide(obj)` 有1个参数，要移除的对象或者索引。  

## Examples 例

- [Basic Slider基础幻灯](http://flexslider.woothemes.com/)
- [Basic Slider customDirectionNav自定义DirectionNav的基础幻灯](http://flexslider.woothemes.com/basic-slider-with-custom-direction-nav.html)
- [Slider w/thumbnail controlNav pattern 水平缩略图controlNav模式](http://flexslider.woothemes.com/thumbnail-controlnav.html)
- [Slider w/thumbnail slider 水平缩略图幻灯](http://flexslider.woothemes.com/thumbnail-slider.html)
- [Basic Carousel 基础循环幻灯](http://flexslider.woothemes.com/basic-carousel.html)
- [Carousel with min and max ranges 带范围的循环幻灯](http://flexslider.woothemes.com/carousel-min-max.html)
- [Video with Vimeo API 视频(Vimeo视频媒体)API](http://flexslider.woothemes.com/video.html)
- [Video with Wistia API 视频(Wistia视频媒体) API](http://flexslider.woothemes.com/video-wistia.html)


## Properties 属性

### namespace: *{new}* 命名空间 *{新}*
`namespace` controls the prefixes attached to elements created by the plugin.  
命名空间控制插件创建的元素的前缀。  
In previous releases, only certain elements were tagged with a prefix class, which was causing class generalization issues for some users.  
在以前的版本中，只有某些元素用前缀类标记，这导致了一些用户的类泛化问题。  
FlexSlider now prefixes all generated elements with the appropriate namespace.  
FlexSlider 现在所有元素产生的前缀都有适当的命名空间。  

*Hint: `namespace` can be an empty string.*  
*提示: m命名空间可以是空的字符串。*  

### selector: *{new}* 滚动项目选择器 *{新}*
The markup structure for FlexSlider has been limited to a "ul.slide li" pattern in previous versions of FlexSlider; no longer.  
FlexSlider的标记结构不再局限"ul.slide li"的模式。  
You can now take full control of the markup structure used for your FlexSlider.  
现在你可以完全控制你的FlexSlider的标记结构。  
The `selector` pattern "{container} > {slide}" is mandatory, allowing the plugin to predictably interpret the selector property.  
`selector`选择期模式"{容器} > {slide}" 是强制的，允许插件预见性的解释选择器属性。  
Omitting the ">" from the selector is not suggested, but is possible if your markup doesn't follow the immediate descendant pattern.  
不建议从选择器中省略">"，除非标记没有遵循直接后代模式。  

*Examples: "section > article", ".slides > .slide", "#hero .slide"*  
*例: "section > article", ".slides > .slide", "#hero .slide"*  

### easing: *{new}* 动画 *{新}*
`easing` allows support for jQuery easing!  
`easing` 允许支持jQuery easing!  
Default options provided by jQuery are "swing" and "linear," but more can be used by included the jQuery Easing plugin.  
jQuery提供默认选项"swing"和"linear"的支持，但是更多选项需要引入jQuery Easing插件才可以使用。  
*If you chose a non-existent easing method, the slider will break.*  
*如果你选择了一个不存在的easing方法，幻灯会终止*  

*Note: You need to set `useCSS: false` to force transitions in browsers that support translate3d.*  
*注: 你需要设置`useCSS:false`强制浏览器支持translate3d。*  

*Optional: [jQuery Easing Plugin](http://gsgd.co.uk/sandbox/jquery/easing/)*  
*可选: [jQuery Easing Plugin](http://gsgd.co.uk/sandbox/jquery/easing/)*

### direction: *{changed}* 左右控制按钮 *{修改}*
Previously called "slideDirection" in v1.8 and below.  
在v1.8及一下版本中该属性叫做"slideDirection"。  

### reverse: *{new}* 反转 *{新}*
`reverse` will reverse the animation direction of the slider. Meaning, horizontal sliders can move from right to left, and vertical sliders can move bottom to top.  
`reverse` 将反转幻灯片动画方向。意思是水平幻灯可以从右向左移动，竖直幻灯可以从下向上移动。  

### smoothHeight: *{new}* 过度高度 *{新}*
`smoothHeight` allows for smooth height transitions between slides. This property currently works for the fade and horizontal slide animation. The property has no effect on horizontal sliding carousels, however.
`smoothHeight`允许幻灯片过渡时的过渡高度。这个属性适用于淡入淡出和水平幻灯动画。然而这个属性对水平旋转木马幻灯没有影响。

### startAt: *{changed}* 初始化第一次显示图片位置 *{修改}*
Previously called "slideToStart" in v1.8 and below.  
在v1.8及其早期版本该参数名为"slideToStart"。  
(0 = first slide)  

### animationSpeed: *{changed}* 滚动动画时长 *{修改}*
Previously called "animationDuration" in v1.8 and below.  
在v1.8及其早期版本该参数名为"animationDuration"。  
如：600,默认单位ms。  


### initDelay: *{new}*  延时初始化 *{新}*
`initDelay` will delay the initial slideshow of a slider, given in milliseconds. The slider will still initialize, generating controls and displaying the first image, but the slideshow will wait until the `initDelay` time has completed before starting the slideshow.  
`initDelay`将延迟初始化幻灯片，指定一个毫秒数。幻灯片仍会初始化生成控件并显示第一个图片，但幻灯片开始运行之前会等待`initDelay`设定的时间。  

### useCSS: *{new}* 使用css *{新}*
`useCSS` allow users to override using CSS3 for animation. Translate3d still has numerous bugs that can crop up and wreak havoc, so this is a great property to play with if you are experiencing unexplainable issues in Webkit browsers.  
`useCSS`允许重写CSS3动画。3d动画仍有很多错误存在，如果你正在经历Webkit浏览器无法解释的问题那么这是一个很好的属性。  

*Hint: Use conditionals to enable/disable the use of CSS3 on desktops and mobile devices. Mobile devices, in my experience, do not share many of the translate3d bugs seen on desktop browsers.*  
*提示：使用条件语句来启用/禁用的台式机和移动设备上的使用CSS3。以我的经验移动设备没有那么多在桌面浏览器上出现的3d动画错误。*  

### touch: *{new}* 触控 *{新}*
`touch` allows users to exclude touch swipe functionality from their sliders.  
`touch`允许用户从他们的幻灯片中排除触控。  

### keyboard: *{changed}*  keys键盘左右方向键控制图片滑动 *{修改}*
Previously called "keyboardNav" in v1.8 and below.  
在v1.8及其早期版本该参数名为"keyboardNav"。  
值：true, //Boolean:left/right keys键盘左右方向键控制图片滑动  

### multipleKeyboard *{new}* 是否允许键盘控制多个 slide *{新}*
`multipleKeyboard` allows users to override the default plugin keyboard behavior, enabling keyboard control of more than one slider on the page.  
`multipleKeyboard`允许用户覆盖插件的默认键盘行为，使键盘可以控制多个滑块页面。  
This means that all visible sliders will animate, at the same time, via keyboard input.  
这意味着所有可见滑块可以通过键盘控制动画。  

*Hint: You can use `multipleKeyboard` to allow keyboard navigation on pages where multiple sliders are present, but only one is visible.*  
*提示: 你可以使用`multipleKeyboard`来允许键盘控制多个滑块的导航，但只有一个是可见的的*  


### mousewheel: *{updated}* 鼠标滚轮控制图片滑动 *{更新}*
`mousewheel` now requires the jQuery Mousewheel plugin.  
`mousewheel`现在需要jQuery Mousewheel插件。  
There are a few reasons for this, but primarily because there is no need for FlexSlider itself to reinvent the awkward complexity of mousewheel interactivity that is handled perfectly by the Mousewheel plugin.  
这有几个原因，但主要是因为FlexSlider本身没有必要重塑由jQuery Mousewheel插件完美处理的滚轮交互性。  

*Required: [jQuery Mousewheel Plugin](https://github.com/brandonaaron/jquery-mousewheel)*
*需要: [jQuery Mousewheel Plugin](https://github.com/brandonaaron/jquery-mousewheel)*

### controlsContainer: *{updated}* 控制容器选择器 *{更新}*
`controlsContainer` is one of the more painstaking, potentially confusing properties within FlexSlider.  
`controlsContainer`是比较难处理的，是FlexSlider的潜在混乱因素。  
First, the property is no longer required to workaround `overflow: hidden` on slide animation.  
首先，滑块的这个属性不再需要`overflow:hidden`。  
Second, the property now accepts a **jQuery object**, giving you precise control over the object you want.  
其次，这个属性现在接受一个**jQuery object**,让你可以精确的控制你想要控制的对象。  
The plugin no longer attempts to guess what element you are selecting.  
插件不再尝试猜测你选择的元素。  

### customDirectionNav: *{new}* 自定义左右方向控制按钮 *{新}*
`customDirectionNav` allows the ability to add custom directional navigation elements. Can be used in conjunction with controlsContainer for pagination controls container.

*[Example of customDirectionNav being used](http://flexslider.woothemes.com/basic-slider-with-custom-direction-nav.html)*

### sync: *{new}* 同步 *{新}*
`sync` is a new property that will allow other slider(s) to hook into the current slider via a given selector. The selector should describe an object that has already been initialized as a FlexSlider. Right now, `sync` will synchronize animation, play, and pause behaviors. 
`sync`是一个新属性，它允许其他滑块通过给定的选择器连接当前的滑块。选择要描述已经初始化为FlexSlider对象。现在，“同步”将同步动画、播放和暂停行为。
More behaviors can be added in the future as the property matures.
随着属性的完善将来会加入更多的同步行为。

*[Example of sync being used](http://flex.madebymufffin.com/examples/basic-carousel.html)*

### asNavFor: *{new}*
Description to be added.

### itemWidth: *{new}*
`itemWidth` is the primary property for the new carousel options. Without this property, your slider is not considered a carousel. To use `itemWidth`, give an integer value of the width of your individual slides. This should include borders and paddings applied to your slides; a total width measurement.

### itemMargin: *{new}*
`itemMargin` describes the gutter between the slide elements. If each slide has a margin-left of 10px, your itemMargin value would be 10. If elements have margin: 0 10px, your itemMargin would be 20.

### minItems: *{new}*
`minItems` describes the minimum number of slide elements that should be visible in the carousel. When the slider reaches the minimum item count, the slides will resize fluidly with the slider.

### maxItems: *{new}*
`maxItems` describes the maximum number of slide elements that should be visible in the carousel. When the slider reaches the maximum item count, the slides will resize fluidly with the sider.

### move: *{new}*
`move` determines how many slides should be animated within the carousel. When left at 0, the slider will animate the number of visible slides. If any value greater than 0 is given, the slider will animate that number of slides in the carousel on each animation interval.

*Hint: The move property will be ignored if the value is higher than the number of visible slides, which can be utilized in responsive design.*

### added: *{new}*
`added()` is a new callback event fired in the new slider.addSlide() function.

### removed: *{new}*
`removed()` is a new callback event fired in the new slider.removeSlide() function.

### allowOneSlide: *{new}*
Boolean. Whether or not you'd like FlexSlider to initialize as usual if only one slide is present.



## 文档
> animation: "slide",             // String: ["fade"|"slide"]，动画效果  
> easing: "swing",                // String: 滚动动画计时函数  
> direction: "horizontal",        // String: 滚动方向 ["horizontal"|"vertical"]  
> reverse: false,                 // Boolean: 翻转 slide 运动方向  
> animationLoop: true,            // Boolean: 是否循环播放  
> smoothHeight: false,            // Boolean: 当 slide 图片比例不一样时  
> // "true": 父类自动适应图片高度  
> // "false": 不自动适应，父类高度为图片的最高高度，默认为false  
>  
> startAt: 0,                     // Integer: 开始播放的 slide，从 0 开始计数  
> slideshow: true,                // Boolean: 是否自动播放  
> slideshowSpeed: 5000,           // Integer: ms 滚动间隔时间  
> animationSpeed: 600,            // Integer: ms 动画滚动速度  
> initDelay: 0,                   // Integer: ms 首次执行动画的延迟  
> randomize: false,               // Boolean: 是否随机 slide 顺序  
>  
> // Usability features  
> pauseOnAction: true,            // Boolean: 用户操作时停止自动播放  
> pauseOnHover: false,            // Boolean: 悬停时暂停自动播放  
> useCSS: true,                   // Boolean: 是否使用 css3 transition  
> touch: true,                    // Boolean: 允许触摸屏触摸滑动滑块  
> video: false,                   // Boolean: 使用视频的 slider，防止 CSS3 3D 变换毛刺  
>  
> // Primary Controls  
> controlNav: true,               // Boolean: 是否创建控制点  
> directionNav: true,             // Boolean: 是否创建上/下一个按钮（previous/next）  
> prevText: "Previous",           // String: 上一个按钮文字，可为html元素  
> nextText: "Next",               // String: 下一个按钮文字，可为html元素  
>  
> // Secondary Navigation  
> keyboard: true,                 // Boolean: 是否开启键盘左（←）右（→）控制  
> multipleKeyboard: false,        // Boolean: 是否允许键盘控制多个 slide  
> mousewheel: true,               // Boolean: 是否开启鼠标滚轮控制  
> pausePlay: false,               // Boolean: 是否创建暂停与播放按钮  
> pauseText: 'Pause',             // String: 暂停按钮文字  
> playText: 'Play',               // String: 播放按钮文字  
>  
> // Special properties  
> controlsContainer: "",          // jQuery Object/Selector  
> manualControls: "",             // jQuery Object/Selector 自定义控制 slider 的元素，  
> // 如 "#tabs-nav li img"，导航数量和 slide 数量一样  
> sync: "",                       // Selector: 关联 slide 与 slide 之间的操作。  
> asNavFor: "",                   // Selector: Internal property exposed for turning the slider into a thumbnail navigation for another slider  
>  
> // Carousel Options  
> itemWidth: 0,                   // Integer: slide 宽度，多个同时滚动时设置  
> itemMargin: 0,                  // Integer: slide 间距  
> minItems: 1,                    // Integer: 最少显示 slide 数, 与 `itemWidth` 相关  
> maxItems: 0,                    // Integer: 最多显示 slide 数, 与 `itemWidth` 相关  
> move: 0,                        // Integer: 一次滚动移动的 slide 数量，0 - 滚动可见的 slide  
>  
> // Callback API  
> start: function(){},            // Callback: function(slider) - 初始化完成的回调  
> before: function(){},           // Callback: function(slider) - 每次滚动开始前的回调  
> after: function(){},            // Callback: function(slider) - 每次滚动完成后的回调  
> end: function(){},              // Callback: function(slider) - 执行到最后一个 slide 的回调  
> added: function(){},            // Callback: function(slider) - slide 添加时触发  
> removed: function(){}           // Callback: function(slider) - slide 被移除时触发  
