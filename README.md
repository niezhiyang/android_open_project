# myNote
笔记 自己看的
### 多渠道打包(脚本打包)
* [VasDolly](https://github.com/Tencent/VasDolly)腾讯出版<br>
针对v1签名方式，利用zip的comment区域
针对v2签名方式，利用apk中的签名块中插入key-value
* [packer-ng-plugin](https://github.com/mcxiaoke/packer-ng-plugin)
下一代Android打包工具，100个渠道包只需要10秒钟 
* [walle](https://github.com/Meituan-Dianping/walle) 美团出品  <br>主要利用修改apk的目录META-INF中添加空文件，由于不需要重新签名，操作非常快
### 6.0动态权限
* [PermissionsDispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher)最早且star最多的一个
* [RxPermissions](https://github.com/tbruyelle/RxPermissions)链式编程
* [easypermissions](https://github.com/googlesamples/easypermissions)google <br>官方的处理方式
* [AndPermission](https://github.com/yanzhenjie/AndPermission) 严振杰的
* [XXPermissions](https://github.com/getActivity/XXPermissions) 里面有所有权限框架的对比
### 网络请求
* [retrofit](https://github.com/square/retrofit)配合 okhttp 是这两年最火的一个请求框架
* [okhttp](https://github.com/square/okhttp) 近两年最火的一个
* [android-async-http](https://github.com/loopj/android-async-http) 比较老牌的网络请求框架
* [okhttp-OkGo](https://github.com/jeasonlzy/okhttp-OkGo) 官网说比 retrofit 更厉害， 也可以配合 rxjava
* [xUtils3](https://github.com/wyouflf/xUtils3) 这个也差不多最老牌的吧  我记得我第一个用的就是他， 然后是 google的 volley 再后来就是 okhttp了
* [volley](https://github.com/google/volley) google的亲儿子
* [okhttputils](https://github.com/hongyangAndroid/okhttputils) 张鸿洋 大神对 okhttp 的一个封装 ，但是现在已经不维护了

### 组件化
* [auto](https://github.com/google/auto) *google出* <br>
* [ARouter](https://github.com/alibaba/ARouter) *阿里出品* <br>
Android平台中对页面、服务提供路由功能的中间件，我的目标是 —— 简单且够用
* [Andromeda](https://github.com/iqiyi/Andromeda) *爱奇艺出品* <br>
采用"接口+数据结构"的方式来实现组件间通信，这种方式相比协议的方式在于实现简单，维护方便.支持ipc
* [WMRouter](https://gi
thub.com/meituan/WMRouter) *美团出品* 
WMRouter是一款Android路由框架，基于组件化的设计思路，有功能灵活、使用简单的特点
* [DeepLinkDispatch](https://github.com/jeasonlzy/okhttp-OkGo) *爱彼迎*
* [ActivityRouter](https://github.com/mzule/ActivityRouter) 个人
* [cc](https://github.com/luckybilly/CC) 个人

### 热修复
* [Tinker](https://github.com/Tencent/tinker/wiki) *腾讯出品*  <br>微信就是用的这个热修复
* [AndFix](https://github.com/alibaba/AndFix) *阿里出品* 
* [Robust](https://github.com/Meituan-Dianping/Robust) *美团*
* [Amigo](https://github.com/eleme/Amigo) *饿了么*
### 插件化
* [DroidPlugin](https://github.com/DroidPluginTeam/DroidPlugin) 已经不维护了
* [RePlugin](https://github.com/Qihoo360/RePlugin) *奇虎360出品* 支持9.0  <br>RePlugin是一套完整的、稳定的、适合全面使用的，占坑类插件化方案，由360手机卫士的RePlugin Team研发，也是业内首个提出”全面插件化“（全面特性、全面兼容、全面使用）的方案
* [VirtualAPK](https://github.com/didi/VirtualAPK) *滴滴出品* 支持9.0  <br>VirtualAPK是滴滴出行自研的一款优秀的插件化框架,支持四大组件
* [DynamicAPK](https://github.com/CtripMobile/DynamicAPK) *携程*  <br>实现Android App多apk插件化和动态加载，支持资源分包和热修复
* [dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk) *任玉刚 任主席*  <br>实现Android App多apk插件化和动态加载，支持资源分包
* [Shadow](https://github.com/Tencent/Shadow) *腾讯 *  <br>零反射全动态Android插件框架
* [Small](https://github.com/wequick/Small)

### 性能优化
* [leakcanary](https://github.com/square/leakcanary/) *square*  <br>检测内存泄露
* [matrix](https://github.com/Tencent/matrix) *腾讯 微信团队*  <br>Matrix 当前监控范围包括：应用安装包大小，帧率变化，启动耗时，卡顿，慢方法，SQLite 操作优化，文件读写，内存泄漏等等
* [ArgusAPM](https://github.com/Qihoo360/ArgusAPM) *360*  <br>ArgusAPM是360手机卫士客户端团队继RePlugin之后开源的又一个重量级开源项目。ArgusAPM是360移动端产品使用的可视化性能监控平台，为移动端APP提供性能监控与管理，可以迅速发现和定位各类APP性能和使用问题，帮助APP不断的提升用户体验。

* [AndroidPerformanceMonitor](https://github.com/markzhai/AndroidPerformanceMonitor) *老的名字BlockCanary*  <br>是一个Android平台的一个非侵入式的性能监控组件，应用只需要实现一个抽象类，提供一些该组件需要的上下文环境，就可以在平时使用应用的时候检测主线程上的各种卡慢问题，并通过组件提供的各种信息分析出原因并进行修复
* [battery-historian](https://github.com/google/battery-historian) *google*  <br>电量优化
* [DoraemonKit](https://github.com/didi/DoraemonKit) *滴滴*  <br>DoraemonKit 是一个功能集合面板，能够让每一个 App 快速接入一些常用的或者你没有实现的一些辅助开发工具、测试效率工具、视觉辅助工具，而且能够完美在 Doraemon 面板中接入你已经实现的与业务紧密耦合的一些非通有的辅助工具，功能强大，接入方便，便于扩展
* [booster](https://github.com/didi/booster) *滴滴*  <br>是一款专门为移动应用设计的易用、轻量级且可扩展的质量优化框架，其目标主要是为了解决随着 APP 复杂度的提升而带来的性能、稳定性、包体积等一系列质量问题
* [alpha](https://github.com/alibaba/alpha) *阿里* Alpha是一个基于PERT图构建的Android异步启动框架，它简单，高效，功能完善。减少Application的启动时间

### 图片压缩
* [Luban](https://github.com/Curzibn/Luban)  可能是最接近微信朋友圈的图片压缩算法
* [Compressor](https://github.com/zetbaitsu/Compressor) 
* [Tiny](https://github.com/Sunzxyong/Tiny) 
 https://github.com/Sunzxyong/Tiny
### 屏幕适配
* [AndroidAutoSize](https://github.com/JessYanCoding/AndroidAutoSize) 由个人对 今日头条 方案的一种封装，业界内比较认可的一种方式
* [AndroidAutoLayout](https://github.com/hongyangAndroid/AndroidAutoLayout) 张鸿洋封装的一套。已经有很长时间不维护了

### 资源压缩（包体积）
* [AabResGuard](https://github.com/bytedance/AabResGuard) *抖音团队* 资源混淆，较少包体积
* [AndResGuard](https://github.com/shwenzhang/AndResGuard) *微信团队* 资源混淆工具大约是在2014年4月实现，并在微信5.4中使用，减少了大约1M的空间。然后在8月在公司内部开源，现以推广到QQ邮箱、QQ空间、手机管家等多个产品中使用
### 优秀的插件
* [ByteX](https://github.com/bytedance/ByteX/blob/master/README_zh.md) 字节
1. 干净地删除某些方法调用，如Log.d
2. R文件常量内联，R文件瘦身；无用Resource资源检查；无用assets检查。
3. 文件流的close检查 等等

* [Hunter](https://github.com/Leaking/Hunter) 里面有全局网络监控，打印出这个方法所有输入参数的值，以及返回值，执行时间
* [Luffy](https://github.com/JieYuShi/Luffy) 全自动埋点，已经不维护了，需要自己二次开发
* [hugo](https://github.com/JakeWharton/hugo) *JakeWharton*  <br>检测方法执行的时间

### native层内存泄漏
* [memory-leak-detector](https://github.com/bytedance/memory-leak-detector) 字节跳动
### 好看实用日志
* [logger](https://github.com/orhanobut/logger)
* [timber](https://github.com/JakeWharton/timber)

### 收集内存
* [KOOM](https://github.com/KwaiAppTeam/KOOM) 快手的高性能线上内存监控方案
* [tailor](https://github.com/bytedance/tailor) 头条西瓜团队。ailor是西瓜Android团队开发的一款通用内存快照裁剪压缩工具，通过它可以在异常时直接dump出一个迷你内存快照。快照中没 有任何敏感信息，更重要的是文件非常小的同时数据也相对完整，非常适合离线分析OOM及其他类型异常的调查定位

### native hook
-  [xHook](https://github.com/iqiyi/xHook) 爱奇艺
-  [bhook](https://github.com/bytedance/bhook) 字节

