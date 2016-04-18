# SlideMenu2Demo

Swift - 侧滑菜单的实现（样例2：仿QQ，菜单带缩放效果）

原文出自：www.hangge.com  转载请保留原文链接：http://www.hangge.com/blog/cache/detail_1035.html

演示另一种样式的实现（模仿手机QQ的侧滑菜单），主页面滑动停靠的过程中会逐渐缩小，同时菜单页也会逐渐移动放大，浮现出来。


主页停靠侧边时尺寸逐渐缩小
（1）定义了新属性 minProportion，表示停靠时的缩小比例。在滑动时，再根据页面的位置实时计算出当前的缩放比例。
（2）在主页面与菜单页之间添加了个黑色遮罩层（blackCover）， 初始化时是不透明的。随着菜单的展开透明度逐渐变为0。这样侧滑菜单有逐渐显示出来的效果。
