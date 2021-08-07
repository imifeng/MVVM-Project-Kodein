# MVVM-Project (Kotlin)
Kodein + Room + ViewModel + LiveData + Work (MVVM)


## Libraries Used

* 使用[Kodein](https://github.com/Kodein-Framework/Kodein-DI) 实现依赖项注入

* [ViewModel ](https://developer.android.com/topic/libraries/architecture/viewmodel) 架构组件为界面控制器提供了 ViewModel 辅助程序类，该类负责为界面准备数据。在配置更改期间会自动保留 ViewModel 对象，以便它们存储的数据立即可供下一个 Activity 或 Fragment 实例使用

* [LiveData ](https://developer.android.com/topic/libraries/architecture/livedata) 是一种可观察的数据存储器类。与常规的可观察类不同，LiveData 具有生命周期感知能力，意指它遵循其他应用组件（如 Activity、Fragment 或 Service）的生命周期。这种感知能力可确保 LiveData 仅更新处于活跃生命周期状态的应用组件观察者。

* 使用[ Room ](https://developer.android.com/training/data-storage/room)将数据保存到本地数据库

* 暂未添加 [ Work Manager ](https://developer.android.com/topic/libraries/architecture/workmanager)调度任务；WorkManager 是一个 API，可供您轻松调度那些即使在退出应用或重启设备后仍应运行的可靠异步任务。WorkManager API 是一个适合用来替换所有先前的 Android 后台调度 API（包括 FirebaseJobDispatcher、GcmNetworkManager 和 JobScheduler）的组件

* [Retrofit 2](https://square.github.io/retrofit) 适用于 Android 和 Java 的类型安全 HTTP 客户端

* [moshi](https://github.com/square/moshi) 是一个适用于 Android 和 Java 的现代 JSON 库， 它可以轻松地将 JSON 解析为 Java 对象。

* [Glide](https://bumptech.github.io/glide) 是一个快速高效的 Android 图像加载库，专注于平滑滚动。 Glide 提供了一个易于使用的 API、一个高性能和可扩展的资源解码管道和自动资源池。

* [StatusBarUtil](https://github.com/laobie/StatusBarUtil) （实现沉浸式状态栏/变色状态栏），是一个为Android App 设置状态栏的工具类， 可以在4.4及其以上系统中实现 沉浸式状态栏/状态栏变色，支持设置状态栏透明度，满足你司设计师的各种要求。



欢迎查看 Hilt依赖注入架构：[MVVM-Project-Hilt](https://github.com/Amifeng/MVVM-Project-Hilt)
