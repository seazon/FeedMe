# Mobilizer 和全文下载
有些 RSS 订阅源的文章只提供摘要，而不是全文，这样的阅读体验并不友好。FeedMe 提供了多种 Mobilizer 来进行全文下载。目前支持 `FeedMe`，`Mercury` 和 `Google Web Light` 3种。`FeedMe` 为 FeedMe 自带 Mobilizer，另外2个是第三方 Mobilizer 服务。

在 FeedMe 中，有2种情况需要用到 Mobilizer。 
1. 在手动/自动同步时使用 Mobilizer 进行全文下载；
2. 在阅读时使用 Mobilizer 进行全文下载。
你可以在下图中看到这2个设置（可以通过侧边栏-订阅-类别/订阅源到达这里）：

<img src="https://github.com/seazon/FeedMe/blob/master/doc/en/imgs/mobilizer_1.png" width="25%" height="25%" />

# 为什么设置了第三方mobilizer，但是文章还是使用FeedMe mobilizer下载的？
因为第三方 Mobilizer 为了保证其服务的可用性，一般都会限制调用频率。如果调用过快或者次数过多，他们就会停止服务。由于 FeedMe 同步时下载频率很高，就可能因此导致第三方 Mobilizer 不可用。所以在同步时，只有自带的 Mobilizer可用。

所以，在`订阅源设置`对话框中的 Mobilizer，只适用于阅读时的下载。见下图。

<img src="https://github.com/seazon/FeedMe/blob/master/doc/en/imgs/mobilizer_2.png" width="25%" height="25%" />

注：Mobilizer：去除网页上一些不重要的元素（头部，侧边及底部的导航或者链接）并重新排版，仅保留正文部分。一般 Mobilizer 得到的文章是由程序算法计算解析得出的，所以不能保证百分百的正确。成熟的 Mobilizer 在正确性上会做的更好，而自带的会差一些。

# Feed 和 Web 显示
在文章界面的右上角，显示着 `Feed/Web`。其中 `Feed` 代表文章内容来自RSS，`Web` 代表文章内容来自源链接。

Web的内容通过源链接重新抓取，并通过Mobilizer解析。一般情况下可以正确解析出正文内容，但也可能解析错误，得到非正文内容。

## 当前是 `Feed` 还是 `Web`？
- 当 `Feed` 为强调色时，说明当前内容是 `Web`。
- 当 `Web` 为强调色时，说明当前内容是 `Feed`。

## 手动切换 feed/web 显示
怎么在文章界面手动切换 feed/web 显示？

### 1. 点击 feed/web 链接
你可以点击右上角的 feed/web 链接。强调色的是链接，另一个是当前页面状态。 

注意：如果 web 页面没有下载，在你第一次点击 web 链接时会下载。使用哪个 Mobilizer 下载？查看`订阅源设置`对话框的文章 Mobilizer 设置。

### 2. `重新加载页面`菜单
`重新加载页面`在更多菜单中。它每次都会从网络下载 web 页面，即使 web 页面已经下载过。 

### 3. 双击
你可以在`设置` - `操纵`中将双击操作设置为`切换 feed/web 页面`。它的行为和点击 feed/web 链接一致。

### 4. 自动加载 web 页面
如果你在`订阅源设置`对话框启用了`阅读时下载 web 页面`，它会在进入文章界面时自动使用你设置的 Mobilizer 来下载全文。

注意：同点击 feed/web 链接，它只会在 web 页面没有下载。当然，如果没有网络，它什么都不会做。

# 默认显示
所以，默认会显示哪个页面？feed 还是 web 页面？
- 默认显示 feed 页面。
- 显示 web 页面，如果你在`订阅源设置`对话框启用了`同步时下载 web 页面`并且同步时顺利下载了改页面。
- 显示 feed 页面，如果你在`订阅源设置`对话框启用了`同步时下载 web 页面`但没有在同步时顺利下载了改页面。
- 显示 web 页面，如果你在`订阅源设置`对话框启用了`阅读时下载 web 页面`并且网络可用。
- 显示 feed 页面，如果你在`订阅源设置`对话框启用了`阅读时下载 web 页面`但网络不可用。

当文章内容在某些功能中使用时，比如`全文分享`或者播放，它同样会遵循以上规则。 

# FeedMe Mobilizer 选择器 （从v4.1开始支持）
`FeedMe Mobilizer` 使用了一个简单的算法来解析一个URL地址中的正文内容。一般在正文内容比较多时可以获得比较准确的解析。但由于网页各式各样，总有这个简单算法解析错误的时候。

在CSS中，选择器用来选择HTML的某一些元素。从v4.1开始，FeedMe会简单的使用一些类选择器的思路来帮助`FeedMe Mobilizer`更准确的定位内容部分。我把这个新功能叫做`FeedMe Mobilizer 选择器`。

## 优点
- 更加准确的解析文章正文内容
- 更少的解析时间

## 缺点
- 需要HTML/CSS知识
- 需要知道如何通过浏览器来定位HTML中某个节点

## 快速指南
1. 确定你需要设置`FeedMe Mobilizer 选择器`的订阅源，它一般是没有提供全文输出并且`FeedMe Mobilizer`不能正确解析。
2. 在桌面浏览器打开这个订阅源的任意一篇文章。
3. 通过查看元素节点，找到包含正文的最小节点，找到可以用来定位的ID或者class
4. 打开FeedMe，打开这个订阅源的订阅管理界面，`Mobilizer`选择`FeedMe`，这时就会显示`FeedMe Mobilizer Selector`部分
5. 输入找到的用来定位的ID或者class，这里分2种情况：
    - 找到的是ID，比如 `content_body`，输入 `#content_body`
    - 找到的是class，比如 `content_body`，输入 `.content_body`
6. 到此为止，设置已经完成。你可以再次打开web看解析是否正确。如果web已经打开过，需要通过文章界面的`Reload page`来重新加载并解析。
