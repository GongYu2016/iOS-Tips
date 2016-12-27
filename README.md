
# iOS-Tips
iOS开发中的一些技巧及注意事项

## StatusBar
* 在info.plist文件中 View controller-based status bar appearance
-> YES，则控制器对状态栏设置的优先级高于application
-> NO，则以application为准，控制器设置状态栏prefersStatusBarHidden是无效的的根本不会被调用

## 调试技巧

* [多个iOS模拟器并行调试](https://github.com/plu/pxctest)

![demo](https://github.com/plu/pxctest/blob/master/static/screencast.gif)

* 初学者使用 CocoaPods 最常见的误区就是认为pod search是在查询线上的最新版本，实际上，这个命令搜索的是本机上的最新版本，并没有联网查询。不信你可以把Wifi关掉搜下，看能不能搜出内容来。如果运行以上命令，没有搜到或者搜不到最新版本，您可以运行以下命令，更新一下您本地的 CocoaPods 源列表。

```
pod repo update
```

## 开源项目

* [Swift+OpenGL ES实现360°全景播放器](https://github.com/Huanhoo/VRDemo-Swift)

![demo](https://github.com/Huanhoo/VRDemo-Swift/blob/master/demo.gif)

* 键盘管理库 [IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager)
