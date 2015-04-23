# BaiduFM-Swift
[![](http://img.shields.io/badge/build-passing-4BC51D.svg)]()
[![](http://img.shields.io/badge/OS%20X-10.10.3-blue.svg)]() 
[![](http://img.shields.io/badge/xcode-6.3-blue.svg)]()
[![](http://img.shields.io/badge/iOS-8.0%2B-blue.svg)]() 
[![](http://img.shields.io/badge/Swift-1.2-blue.svg)]() 
[![CocoaPods compatible](https://img.shields.io/badge/CocoaPods-compatible-4BC51D.svg)](https://github.com/cocoapods/cocoapods)

百度FM, swift语言实现，基于最新xcode6.3+swift1.2,初步只是为了实现功能，代码比较粗燥，后面有时间会整理。

##API接口申明
-本APP接口使用百度FM非公开API,音乐版权归百度所有

##功能

-可以下拉刷新,上拉加载更多歌曲列表

-歌词自动滚动

-实时显示歌曲播放进度

-暂停继续播放

-上一曲下一曲

-歌曲类型列表

-分类歌曲列表

-支持后台播放

-锁屏显示歌曲专辑信息

-锁屏控制音乐下一曲/上一曲、暂停播放

-新增收藏列表，最近播放列表，下载歌曲列表


##项目截图
- 锁屏显示、播放控制![项目截图0](https://github.com/belm/BaiduFM-Swift/blob/master/BaiduFM-Swift_00.jpg?raw=true)

- 项目首页![项目截图1](https://github.com/belm/BaiduFM-Swift/blob/master/BaiduFM-Swift_01.jpg?raw=true)

- 歌曲分类![项目截图2](https://github.com/belm/BaiduFM-Swift/blob/master/BaiduFM-Swift_02.jpg?raw=true)

- 歌曲列表![项目截图3](https://github.com/belm/BaiduFM-Swift/blob/master/BaiduFM-Swift_03.jpg?raw=true)

##项目使用注意事项
-项目里使用[COCOAPODS](https://github.com/cocoapods/cocoapods)管理第三方库，运行前请执行pod install安装依赖库

##项目使用的第三方库

-[网络库Alamofire](https://github.com/Alamofire/Alamofire)

-[JSON解析SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)

-[SQLite数据库FMDB](https://github.com/ccgus/fmdb)

-[异步Async](https://github.com/duemunk/Async)

-[MJRefresh](https://github.com/CoderMJLee/MJRefresh)

-[文字效果LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel)

##使用的swift知识点
-网络请求

-JSON解析

-swift正则

-swift单例

-下拉刷新、上拉加载更多MJRefresh，歌曲进度UIProgressView，歌词滚动UITextView

-闭包

-get，set，didSet

-使用MPMoviePlayerController在线播放网络mp3 

##待完成功能
-下载歌曲到本地(完善中)

-收藏喜欢的音乐(已经完成)

-最近播放的音乐(已经完成)

-背景播放支持(已经完成)

-播放音乐改用AVAudioPlayer

-第三方库合并(已经改用[COCOAPODS](https://github.com/cocoapods/cocoapods)管理)

##联系我
- [QQ邮箱](mailto:belm@vip.qq.com)

