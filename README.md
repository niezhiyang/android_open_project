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
