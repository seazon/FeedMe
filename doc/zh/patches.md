# 4.2.0
###### 2024年3月4日
- [新增] 支持本地RSS。
- [新增] 添加Miniflux服务。
- [新增] 部分界面重新设计。
  - 登录界面。
  - 订阅列表和详细信息界面。
  - 新的 OPML 提要选择对话框。
  - 将`设置`-`同步`-`高级`移至订阅列表界面。
- [新增] Feedly 支持编辑订阅。
- [优化] FeedMe 不再响应来自外部应用的 http/https URL 意图。 https://github.com/seazon/FeedMe/issues/678
- [优化] 增加全屏播放视频时禁用自动横向的选项(`设置` - `界面` - `Full Screen Playback`)。 https://github.com/seazon/FeedMe/issues/661
- [优化] 支持Feedbin缩略图。 https://github.com/seazon/FeedMe/issues/646
- [优化] 调整视频高度。 https://github.com/seazon/FeedMe/issues/675
- [优化] 始终在导航侧显示同步图标。 https://github.com/seazon/FeedMe/issues/682
- [优化] 调整加载图标偏移。 https://github.com/seazon/FeedMe/issues/681
- [修复] 修复 OPML 导入在 Android 14 上不起作用的问题。
- [修复] 其他小更新。

### 4.1.8
###### 2024-1-18
- [修复] 修复导航上一篇或下一篇文章时滚动冻结的问题。 https://github.com/seazon/FeedMe/issues/671

### 4.1.7
###### 2024-1-5
- [修复] 修复崩溃问题。

### 4.1.6
###### 2023-12-31
- [修复] 修复视频全屏后异常退出的问题。 https://github.com/seazon/FeedMe/issues/665

### 4.1.5
###### 2023-12-07
- [优化] 优化 HTML code 标签的样式。
- [优化] `设置`-`操纵`中新增选项：禁止在文章页面打开图片。
- [修复] 修复 HTML code 标签中的解析错误。 https://github.com/seazon/FeedMe/issues/659
- [修复] 修复一些崩溃问题。

### 4.1.4
###### 2023-11-27
- [修复] 修复在 Android 14 上播放音频时崩溃的问题。
- [修复] 修复`Split Action Bar`描述错误。 https://github.com/seazon/FeedMe/issues/660

### 4.1.3
###### 2023-11-12
- [修复] 修复LED颜色配置问题。https://github.com/seazon/FeedMe/issues/654

### 4.1.2
###### 2023-11-9
- [优化] 改进NAV侧标顶部布局。
- [优化] 改进确认弹窗。
- [修复] 修复pre标签格式问题。https://github.com/seazon/FeedMe/issues/652

### 4.1.1
###### 2023-10-23
- [修复] 更新库版本。

# 4.1
###### 2023-10-21
- [新增] FeedMe Mobilizer 选择器。 https://github.com/seazon/FeedMe/issues/622
- [新增] 新的小部件：播放器小部件。
- [优化] `设置`-`界面`优化`紧凑布局`，支持更多布局选项。
- [优化] 更新开关样式。
- [修复] 修复 FeedMe Mobilizer 的图像解析错误问题。 https://github.com/seazon/FeedMe/issues/364

### 4.0.4
###### 2023-10-8
- [优化] 在备份中包含荧光标签数据。 https://github.com/seazon/FeedMe/issues/615
- [修复]修复 Feedbin mobilizer 的问题。 https://github.com/seazon/FeedMe/issues/602 https://github.com/seazon/FeedMe/issues/577

### 4.0.3
###### 2023-10-6
- [修复] 修复不能设置同步间隔为4小时的问题。 https://github.com/seazon/FeedMe/issues/630
- [修复] 修复内置浏览器深色模式不起作用的问题。
- 
### 4.0.2
###### 2023-9-15
- [优化] 支持设置文章列表卡片的边距。
- [修复] 修复启动时没有显示侧栏的问题。 https://github.com/seazon/FeedMe/issues/612
- [修复] 修复启动时同步不起作用的问题。 https://github.com/seazon/FeedMe/issues/607
- [修复] 修复后退动作错误逻辑。

### 4.0.1
###### 2023-9-2
- [优化] 文章页边距最小值调整。
- [修复] 修复文章页边距过大的问题。
- [修复] 修复当打开app时自动滚动到上次阅读位置的问题。 https://github.com/seazon/FeedMe/issues/591
- [其他] 移除广告。

### 4.0.0
###### 2023-8-30
- [修复] 修复导入导出 OPML 失败的问题。

### 4.0.0-Canary-11
###### 2023-8-20
- [DE-BUFF] 在文章列表中显示广告。
- [优化] 添加忽略电池优化白名单的提示。 https://github.com/seazon/FeedMe/issues/91#issuecomment-1683809364
- [优化] 同步间隔新增选项：10分钟。
- [优化] 禁用“紧凑布局”将始终显示单屏。 https://github.com/seazon/FeedMe/issues/556#issuecomment-1660290318
- [修复] 修复图像以音乐格式显示。 https://github.com/seazon/FeedMe/issues/364
- [修复] 修复蓝牙控件不起作用的问题。 https://github.com/seazon/FeedMe/issues/581
- [修复] 修复到达底部时无法自动标记已读的问题。 https://github.com/seazon/FeedMe/issues/574

### 4.0.0-Canary-10
###### 2023-8-2
- [fix] Fix mobilizer not work issue. https://github.com/seazon/FeedMe/issues/567

### 4.0.0-Canary-9
###### 2023-8-1
- [新增] 添加紧凑布局选项。 https://github.com/seazon/FeedMe/issues/556
- [修复] 修复更新同步间隔时崩溃的问题。<b>如果您从 Canary 8 升级，需要更新`设置` - `缓存` - `阅读列表`以避免再次崩溃。</b> https://github.com/seazon/FeedMe/issues/561
- [修复] 修复图像显示为音乐icon的问题。 https://github.com/seazon/FeedMe/issues/364
- [修复] 修复从`加星条目”切换到“所有条目”后菜单栏消失的问题。 https://github.com/seazon/FeedMe/issues/560
- [修复] 修复退出全屏视频后侧边栏不可点击的问题。 https://github.com/seazon/FeedMe/issues/554

### 4.0.0-Canary-8
###### 2023-7-29
- [优化] 添加翻页百分比选项。
- [优化] 用于强调色和荧光标签颜色的新颜色选择器。
- [优化] 确认框按钮垂直摆放。
- [优化] 在 url 对话框中显示 url。 https://github.com/seazon/FeedMe/issues/517#issuecomment-1629953259
- [优化] 导航现在可以通过滑动关闭。 https://github.com/seazon/FeedMe/issues/546
- [优化] 优化选中条目的颜色。 https://github.com/seazon/FeedMe/issues/538
- [修复] 修复双面板情况下无法标记已读的问题。 https://github.com/seazon/FeedMe/issues/543
- [修复] 关闭沉浸模式时始终显示工具栏。
- [修复] 增加导航栏底部空间。 https://github.com/seazon/FeedMe/issues/553

### 4.0.0-Canary-7
###### 2023-7-14
- [优化]记住文章阅读位置。 https://github.com/seazon/FeedMe/issues/526
- [优化]更好的处理界面和导航栏的关系当导航栏位于屏幕左侧或右侧时。
- [修复]修复内置浏览器分享时崩溃的问题。 https://github.com/seazon/FeedMe/issues/522#issuecomment-1605891128
- [修复]修复无法加载文章列表第二页的问题。 https://github.com/seazon/FeedMe/issues/542

### 4.0.0-Canary-6
###### 2023-6-22
- [修复]修复文章列表中出现大空白的问题。 https://github.com/seazon/FeedMe/issues/532

### 4.0.0-Canary-5
###### 2023-6-21
- [修复] 修复操作栏菜单显示不正确的问题。 https://github.com/seazon/FeedMe/issues/517#issuecomment-1594359875
- [修复] 修复文章列表从其他屏幕返回时自动滚动的问题。 https://github.com/seazon/FeedMe/issues/528

### 4.0.0-Canary-4
###### 2023-6-17
- [新增] 点击文章页面的feed标题可以进入该feed的文章列表页面。 https://github.com/seazon/FeedMe/issues/523
- [优化] 更新沉浸模式。 https://github.com/seazon/FeedMe/issues/517#issuecomment-1590289087
- [修复] 修复 Tiny Tiny RSS 无法同步到未读条目的问题。 https://github.com/seazon/FeedMe/issues/525
- [修复] 修复旋转屏幕后视频停止播放的问题。 https://github.com/seazon/FeedMe/issues/517#issuecomment-1586380529
- [修复] 修复分享到微信崩溃的问题。 https://github.com/seazon/FeedMe/issues/522#issuecomment-1593792701

### 4.0.0-Canary-3
###### 2023-6-15
- [优化]更新中文。 https://github.com/seazon/FeedMe/issues/517#issuecomment-1590312904
- [修复]修复文章页菜单没有更新的问题。 https://github.com/seazon/FeedMe/issues/517#issuecomment-1589336638
- [修复]修复下拉刷新不起作用的问题。 https://github.com/seazon/FeedMe/issues/517#issuecomment-1589351824

### 4.0.0-Canary-2
###### 2023-6-13
- [修复]文章列表中的强调背景色问题。 https://github.com/seazon/FeedMe/issues/517#issuecomment-1586292674
- [修复]左右滑动功能名称与实际功能不匹配的问题。 https://github.com/seazon/FeedMe/issues/517#issuecomment-1587651850

# 4.0.0-Canary-1
###### 2023-6-11
#### 基于 Material You 的新界面
- 卡片扁平化，圆角化 *
- 强调色在深色模式下使用低饱和度颜色
- 启动图标支持 Material You (Android 13+)
#### 大屏适配
- 根据屏幕尺寸展示不同布局
- 键盘快捷键支持 *
#### 音频
- 支持直接流媒体播放，不需要下载
- 音频支持跳过静音
- sleep time 支持单集结束
- 支持播放搜索到的，未订阅的单集
- 移除播放界面的加星功能
- 播客下载可配置
#### 视频
- 视频支持全屏播放
#### 订阅
- 输入某些网站地址时，自动转成rss地址 *
#### 其他
- 标记已读优化
  - 长按标记所有已读时，弹出更多选项（标记一天前为已读，标记一周前为已读）
  - 长按文章除了 标记以上已读外，新增 标记以下已读
- 移除文章页图片占满宽度的特性及设置项，现在总是和文字对齐
- 优化favicon显示 *
- 文章段落目录TOC *
- 新应用内支付商品：榴莲
- 内置浏览器打开外部链接时，会有提示，并且可以记住你的选择。你也可以在设置-缓存-清除默认操作 重置。

`*` 表示功能可用，但未来版本中还会继续完善