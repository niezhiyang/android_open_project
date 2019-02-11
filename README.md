# myNote
笔记 自己看的
### 多渠道打包(脚本打包)
* [VasDolly](https://github.com/Tencent/VasDolly)腾讯出版<br>
针对v1签名方式，利用zip的comment区域
针对v2签名方式，利用apk中的签名块中插入key-value
* [packer-ng-plugin](https://github.com/mcxiaoke/packer-ng-plugin)
下一代Android打包工具，100个渠道包只需要10秒钟 
* [walle](https://github.com/Meituan-Dianping/walle) 美团出品  主要利用修改apk的目录META-INF中添加空文件，由于不需要重新签名，操作非常快
### 6.0动态权限
* [PermissionsDispatcher](https://github.com/permissions-dispatcher/PermissionsDispatcher)最早且star最多的一个
* [RxPermissions](https://github.com/tbruyelle/RxPermissions)链式编程
* [easypermissions](https://github.com/googlesamples/easypermissions)google 官方的处理方式
* [AndPermission](https://github.com/yanzhenjie/AndPermission) 严振杰的
### 网络请求
* [retrofit](https://github.com/square/retrofit)配合 okhttp 是这两年最火的一个请求框架
* [okhttp](https://github.com/square/okhttp) 近两年最火的一个
* [android-async-http](https://github.com/loopj/android-async-http) 比较老牌的网络请求框架
* [okhttp-OkGo](https://github.com/jeasonlzy/okhttp-OkGo) 官网说比 retrofit 更厉害， 也可以配合 rxjava
* [xUtils3](https://github.com/wyouflf/xUtils3) 这个也差不多最老牌的吧  我记得我第一个用的就是他， 然后是 google的 volley 再后来就是 okhttp了
* [volley](https://github.com/google/volley) google的亲儿子
* [okhttputils](https://github.com/hongyangAndroid/okhttputils) 张鸿洋 大神对 okhttp 的一个封装 ，但是现在已经不维护了

### 组件化
* [ARouter](https://github.com/alibaba/ARouter) *阿里出品* 
Android平台中对页面、服务提供路由功能的中间件，我的目标是 —— 简单且够用
* [Andromeda](https://github.com/iqiyi/Andromeda) *爱奇艺出品* 
采用"接口+数据结构"的方式来实现组件间通信，这种方式相比协议的方式在于实现简单，维护方便.支持ipc
* [WMRouter](https://github.com/meituan/WMRouter) *美团出品* 
WMRouter是一款Android路由框架，基于组件化的设计思路，有功能灵活、使用简单的特点
* [DeepLinkDispatch](https://github.com/jeasonlzy/okhttp-OkGo) *爱彼迎*
* [ActivityRouter](https://github.com/mzule/ActivityRouter) 个人
* [cc](https://github.com/luckybilly/CC) 个人

### 热修复
* [Tinker](https://github.com/Tencent/tinker/wiki) *腾讯出品*  微信就是用的这个热修复
* [AndFix](https://github.com/alibaba/AndFix) *阿里出品* 
* [Robust](https://github.com/Meituan-Dianping/Robust) *美团*
* [Amigo](https://github.com/eleme/Amigo) *饿了么*
### 插件化
* [RePlugin](https://github.com/Qihoo360/RePlugin) *奇虎360出品* 支持9.0  RePlugin是一套完整的、稳定的、适合全面使用的，占坑类插件化方案，由360手机卫士的RePlugin Team研发，也是业内首个提出”全面插件化“（全面特性、全面兼容、全面使用）的方案
* [VirtualAPK](https://github.com/didi/VirtualAPK) *滴滴出品* 支持9.0  VirtualAPK是滴滴出行自研的一款优秀的插件化框架,支持四大组件
* [DynamicAPK](https://github.com/CtripMobile/DynamicAPK) *携程*  实现Android App多apk插件化和动态加载，支持资源分包和热修复
* [dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk) *任玉刚 任主席*  实现Android App多apk插件化和动态加载，支持资源分包
### 性能优化
* [leakcanary](https://github.com/square/leakcanary/) *square*  检测内存泄露
* [matrix](https://github.com/Tencent/matrix) *腾讯 微信团队*  Matrix 当前监控范围包括：应用安装包大小，帧率变化，启动耗时，卡顿，慢方法，SQLite 操作优化，文件读写，内存泄漏等等
* [ArgusAPM](https://github.com/Qihoo360/ArgusAPM) *360*  ArgusAPM是360手机卫士客户端团队继RePlugin之后开源的又一个重量级开源项目。ArgusAPM是360移动端产品使用的可视化性能监控平台，为移动端APP提供性能监控与管理，可以迅速发现和定位各类APP性能和使用问题，帮助APP不断的提升用户体验。
* [hugo](https://github.com/JakeWharton/hugo) *JakeWharton*  检测方法执行的时间
* [AndroidPerformanceMonitor](https://github.com/markzhai/AndroidPerformanceMonitor) *老的名字BlockCanary*  是一个Android平台的一个非侵入式的性能监控组件，应用只需要实现一个抽象类，提供一些该组件需要的上下文环境，就可以在平时使用应用的时候检测主线程上的各种卡慢问题，并通过组件提供的各种信息分析出原因并进行修复
