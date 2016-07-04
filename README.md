github整理

## Objective-C
### UICollectionView
* https://github.com/awdigital/AWCollectionViewSlidingDoors
	类似于开眼滑动效果
* https://github.com/molon/MLLayout  
	* 中文介绍
	* Flexbox是现今移动端最优的布局方式，像componentkit, AsyncDisplayKit, React Native, weex等等优秀的开源库都在使用此种布局方式。
	* React Native和weex以及MLLayout都一样是基于facebook开源facebook/css-layout的c实现。
	*	MLLayout的一些代码实现是借鉴于React Native，例如布局计算结果进行默认像素对齐，提升渲染性能。
	*	对以往纯代码布局的开发者而言，MLLayout也可以作为仅仅用来以语义化的形式快速计算布局结果的工具，像对关联的view的frame进行设置，再次调整啊这些都可以自己来做，也可以通过提供的方法自动设置。
	*	MLTagViewFrameRecord可以记录当前的布局结构，但是前提是需要缓存frame的view需要有独特的tag用以之后将记录应用到对应的view上。
	*	MLTagViewFrameRecord相关的TableView和TableViewCell呢，提供了自动缓存cell布局(当然顺带也有高度啦)的实现，这样的话能保证同一行的布局只会计算一次，除非显式reload。这个能大大的提高列表的滚动性能。
	*	FlexBox教程: http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html?utm_source=tuicool 
 * https://github.com/jamztang/CSStickyHeaderFlowLayout 
 * https://github.com/betzerra/MosaicLayout MosaicLayout using UICollectionViews
 * 
### UITableView

### Video
* https://github.com/hanton/HTY360Player Open Source iOS 360 Degree Panorama Video Player. https://itunes.apple.com/hk/app/360-vr-player/id1061464612?mt=8

### 日常必备
* https://github.com/CoderJackyHuang/HYBHelperKit UIBlockKit、UIMakerKit、UIHelperKit、CommonKit、FoundationKit、Controllers等集于一身的神器！
	* UIBlockKit：将常用的UI控件变成block版本，以辅助UIMasonryMaker生成最简单的版本
	* FoundationKit：主要扩展日常使用到的基础类，添加分类，追加常用的API
	*	UIMasonryMaker：基于Masonry生成控件，以简化代码，增加可读性
	*	Constants：经常使用到的常量定义
	*	Controllers：辅助控制器，比如用于测试期使用的接口baseurl访问和建立测试中心入口
	* 等等
* 

### 图文混排
* https://github.com/waynezxcv/Gallop
Gallop是一个功能强大、性能优秀的图文混排框架。
* 

### 网络/通讯
* https://github.com/Soulghost/SGWiFiUpload 通过WiFi将电脑上传文件到手机
* http://www.jianshu.com/p/e69d77d97a5e zip解压

### 自动化打包
* https://github.com/debugtalk/JenkinsTemplateForApp 用 Jenkins 搭建 iOS/Android 持续集成打包平台

### 架构/设计模式
* http://wereadteam.github.io/2016/06/30/Aspects/ 面向切面编程之 Aspects 源码解析及应用

## Swift




