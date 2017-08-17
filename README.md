不定期把相关知识点进行整理,发布到[Issues](https://github.com/soulrelay/InterviewMemoirs/issues)，你的star是我前进的动力！

# InterviewMemoirs

# <font color=#C4573C size=5 face="黑体">前言</font>

写这篇面试回忆录的目的：
>* 梳理一下面试过程的知识点，为了以后可以更直观地回忆
>* 希望给正在或者准备面试的朋友提供一些帮助

其它：
>* 时间周期:【2017／4 -- 2017／6】
>* 来源: 【感谢「奔腾的兔子」和「剑胆诗魂」的友情赞助】
>* 主要面向人群: 面试【高级工程师】或者【资深工程师】等相关职位
>* 没有严格按照一面、二面、三面来区分

# <font color=#C4573C size=5 face="黑体">目录</font>

## <font color=#C4573C size=4 face="黑体">腾讯OMG</font>

>* ☐ synchronize用法
>* ☐ volatile用法
>* ☐ 动态权限适配方案，权限组的概念
>* ☐ 网络请求缓存处理，okhttp如何处理网络缓存的
>* ☐ 图片加载库相关，bitmap如何处理大图，如一张30M的大图，如何预防OOM
>* ☐ 进程保活
>* ☐ listview图片加载错乱的原理和解决方案
>* ☐ https相关，如何验证证书的合法性，https中哪里用了对称加密，哪里用了非对称加密，对加密算法（如RSA）等是否有了解

## <font color=#C4573C size=4 face="黑体">阿里巴巴</font>

>*  ☐ LRUCache原理
>*  ☐ 图片加载原理
>*  ☐ 模块化实现（好处，原因）
>*  ☐ JVM 
>*  ☐ 视频加密传输
>*  ☐ 统计启动时长,标准
>*  ☐ 如何保持应用的稳定性
>*  ☐ ThreadLocal 原理
>*  ☐ 谈谈classloader
>*  ☐ 动态布局
>*  ☐ 热修复,插件化
>*  ☐ HashMap源码,SpareArray原理
>*  ☐ 性能优化,怎么保证应用启动不卡顿
>*  ☐ 怎么去除重复代码
>*  ☐ SP是进程同步的吗?有什么方法做到同步
>*  ☐ 介绍下SurfView
>*  ☐ HashMap实现原理，ConcurrentHashMap 的实现原理
>*  ☐ BroadcastReceiver，LocalBroadcastReceiver 区别
>*  ☐ Bundle 机制
>*  ☐ Handler 机制
>*  ☐ android 事件传递机制
>*  ☐ 线程间 操作 List
>*  ☐ App启动流程，从点击桌面开始
>*  ☐ 动态加载
>*  ☐ 类加载器
>*  ☐ OSGI
>*  ☐ Https请求慢的解决办法，DNS，携带数据，直接访问IP
>*  ☐  GC回收策略
>*  ☐  画出 Android 的大体架构图 
>*  ☐  描述清点击 Android Studio 的 build 按钮后发生了什么
>*  ☐  大体说清一个应用程序安装到手机上时发生了什么；
>*  ☐  对 Dalvik、ART 虚拟机有基本的了解；
>*  ☐  Android 上的 Inter-Process-Communication 跨进程通信时如何工作的；
>*  ☐  App 是如何沙箱化，为什么要这么做；
>*  ☐  权限管理系统（底层的权限是如何进行 grant 的）；
>*  ☐  进程和 Application 的生命周期；
>*  ☐  系统启动流程 Zygote进程 –> SystemServer进程 –> 各种系统服务 –> 应用进程 
>*  ☐  recycleview listview 的区别,性能

## <font color=#C4573C size=4 face="黑体">滴滴</font>

>* ☐ MVP
>* ☐ 广播（动态注册和静态注册区别，有序广播和标准广播）
>* ☐ service生命周期
>* ☐ handler实现机制（很多细节需要关注：如线程如何建立和退出消息循环等等）
>* ☐ 多线程（关于AsyncTask缺陷引发的思考）
>* ☐ 数据库数据迁移问题
>* ☐ 设计模式相关（例如Android中哪里使用了观察者模式，单例模式相关）
>* ☐ 微信的聊天数据在本地都是加密处理的（防止root了被破解），设计一个类似的本地数据存储系统
>* ☐ x个苹果，一天只能吃一个、两个、或者三个，问多少天可以吃完
>* ☐ Android相关你最擅长哪一块
>* ☐ TCP与UDP区别与应用（三次握手和四次挥手）涉及到部分细节（如client如何确定自己发送的消息被server收到） HTTP相关  提到过Websocket 问了WebSocket相关以及与socket的区别
>* ☐ 是否熟悉Android jni开发，jni如何调用java层代码
>* ☐ 进程间通信的方式
>* ☐ java注解
>* ☐ 计算一个view的嵌套层级
>* ☐ 项目组件化的理解
>* ☐ 基于自身工作经验和计算机相关知识，给出 移动端地图局部加载 瓦片大小的像素大小估值
>* ☐ 多线程断点续传原理
>* ☐ Android系统为什么会设计ContentProvider，进程共享和线程安全问题
>* ☐ jvm相关
>* ☐ Android相关优化（如内存优化、网络优化、布局优化、电量优化、业务优化）
>* ☐ EventBus实现原理

## <font color=#C4573C size=4 face="黑体">美团</font>

>* ☐ 线程挂起，休眠，释放资源相关，唤醒，线程同步，数据传递，问了很多线程的问题，问了20分钟大概
>* ☐ static synchronized 方法的多线程访问和作用，同一个类里面两个synchronized方法，两个线程同时访问的问题
>* ☐ 内部类和静态内部类和匿名内部类，以及项目中的应用
>* ☐ 泛型是什么以及在项目中的应用
>* ☐ handler发消息给子线程，looper怎么启动
>* ☐ down、move、up事件的传递
>* ☐ activity栈
>* ☐ 封装view的时候怎么知道view的大小
>* ☐ intent-filter
>* ☐ arraylist和linkedlist的区别，以及应用场景
>* ☐ 怎么启动service，service和activity怎么进行数据交互
>* ☐ 下拉状态栏是不是影响activity的生命周期，如果在onStop的时候做了网络请求，onResume的时候怎么恢复
>* ☐ view渲染

# <font color=#C4573C size=5 face="黑体">总结</font>

共同点：
>* 对基础性、原理性的东西比较重视
>* 具体问题的解决能力、项目的架构能力

不同点：
>* 公司不同、产品业务线不同，所以涉及的技术重点和方向不同

思考：
>* 有些东西你不仅要懂，而且要能够很好地表达出来，能够让面试官认可你的理解，例如Handler机制，这个是面试必问之题
>* 有些晦涩的点，或许它只活在面试当中，实际工作当中你压根不会用到它，但是你要知道它是什么东西

### 今日头条
>* ☐ 快速排序
>* ☐ JSON字符串解析算法及优化
>* ☐ ABC三个线程，C线程要等A和B线程的结果，AB并行，问，跟什么数据结构类似....，不是问生产者消费者或者信号量什么的，>
>* ☐ 线程同步的问题，常用的线程同步
>* ☐ 问项目，根据项目引申：主要有Asynctask和线程池，多进程以及IPC，GC相关（四种引用，怎么判断哪些内存该GC，GC算法），why，when，how  这些都是要从项目里面举出来例子
>* ☐ 图片加载三级缓存，有一个功能，做一个能放大缩小的图片查看器，加载一张巨大的图片，怎么做
>* ☐ 图片加载框架优劣比较，以及之前项目选用加载框架时候的考虑
最佳答案：https://github.com/soulrelay/ImageLoaderUtil
>* ☐ 网络请求相关，主要是网络请求优化。网络请求的时候遇到的问题

总结：一般一面主要考基础知识，以及基于基础知识解决问题的能力
  
 >* ☐ ListView性能优化，以及ListView的各种原理
 >* ☐ RecyclerView优点，原理
 >* ☐ 怎么做上传下载的断点续传
 >* ☐ EventBus原理
 >* ☐ 四种线程池区别，以及常见应用场景，线程池的深入了解
 >* ☐ CoordinatorLayout、CollapsingToolbarLayout原理以及使用
 >* ☐ 数据库性能优化
 >* ☐ ManiFest原理，APP启动流程，APK打包流程
  
  总结：二面主要是看着做的APP问的，APP里涉及到的技术，不管是不是自己负责的模块，只要面试官感兴趣都会问。各种问题最终都要问到底层实现或者原理。
  
  
### 小米
 >* ☐ 求一个字符串的最长回文
 >* ☐ 给定一个数，以及有序数组，求出来数组里面两个数的和等于给定数的下标
 >* ☐ 二叉树中序遍历，深度优先广度优先，不用递归算法的方法
>* ☐ 求二叉树第k层节点个数；
 >* ☐ 实现一个栈push，pop，getMaxElementValue，时间复杂度要求0（1）
 >* ☐ 有序数组0（n）时间复杂度求一组和为sum的数组下标
>* ☐ AsyncTask内部实现，关注默认线程池是一个串行的线程池；
>* ☐ 事件的传递方式，View，ViewGroup
>* ☐ 讲解Activity和Window，View的关系，以及DecorView结构
>* ☐ 自定义View里面OnMeasure参数的意义
>* ☐ 讲解一下HandlerThread

总结：小米每一面都会至少有一个算法题

### 知乎/猎豹
>* ☐ Activity的四种启动模式以及相关概念，Activity栈，常见情境下的生命周期分析，异常关闭页面之后的恢复
>* ☐ Service基础概念，生命周期，通信。四大组件是基础，常见问题都要掌握
>* ☐  IPC
>* ☐ 同步的问题，常见的那些，锁机制，sychronized关键字，concurrent包下的数据结构，atom包下的数据结构
>* ☐ HashMap原理
>* ☐ Handler，包括Looper，MessageQueue，ThreadLocal这些类要详细的看
>* ☐ ArrayList，LinkedList源码要看
>* ☐ View的事件传递机制，要彻底弄透彻，可问的问题很多
>* ☐ Asynctask和线程池
>* ☐ JVM   GC算法，问得比较浅
>* ☐ JVM  类加载过程，问得比较浅
>* ☐  DexClassLoader和PathClassLoader的区别

总结：两家面试差不多，都是基础问题，各种常见套路


### 网易
>* ☐ 求笛卡尔积
>* ☐ 单词反转
>* ☐ 两个有序数组，时间复杂度最好的情况下，合并成一个数组
>* ClassLoader，类加载相关问题，例如继承、static修饰的这些在类加载时候的实际应用
>* 内部类，静态内部类，匿名内部类在加载时候的相关过程
>* 直接引用和符号引用相关
>* android dalvik虚拟机里的类加载
>* scrollview和listview的区别
>* 热修复/插件化（因为简历上写了这两个，所以导致面试官非常有兴趣，一个劲地问，后来才发现面试官就是搞这一块的，教训是，一定要非常了解才能写啊，千万不要乱写T T）

总结：Android基础知识问的较少，主要问的Java基础和JVM基础

![这里写图片描述](http://img.blog.csdn.net/20170612224924027?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvczAwMzYwM3U=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

>* 我的CSDN博客地址：[http://blog.csdn.net/s003603u](http://blog.csdn.net/s003603u)
>* 我的GitHub地址：[https://github.com/soulrelay](https://github.com/soulrelay)
>* 我的简书地址：[http://www.jianshu.com/u/514ca03bbc17](http://www.jianshu.com/u/514ca03bbc17)
