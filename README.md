
# iOS-Tips
iOS开发中的一些技巧及注意事项

## StatusBar
* 在info.plist文件中 View controller-based status bar appearance
-> YES，则控制器对状态栏设置的优先级高于application
-> NO，则以application为准，控制器设置状态栏prefersStatusBarHidden是无效的的根本不会被调用
