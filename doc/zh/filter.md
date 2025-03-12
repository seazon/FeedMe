从2.4版本开始，FeedMe支持在同步时对新文章进行过滤，把你不想读的文章自动标记为已读，来节省你的阅读时间。对每个订阅源，你可以添加不同的的过滤。

过滤设置在订阅源的设置界面。你可以看到左侧是一个切换开关，可以以不同的方式来对这个订阅源进行过滤。下面是填写过滤关键字的文本框。

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/filter_1.png" width="25%" height="25%" />

## 过滤方式
- `保留`：仅保留满足关键字的文章，其它文章标记为已读
- `过滤`：仅将满足关键字的文章标记为已读

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/filter_2.png" width="25%" height="25%" /> <img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/filter_3.png" width="25%" height="25%" />

当某个源你只关心含有某些关键字的文章时，你可以使用`保留`方式；当某个源你不想看某些关键字时，你可以使用`过滤`方式。

## 文本框
- 当你的关键字是2个词的组合，可以使用`+`
- 当你需要设置超过1个关键字时，可以使用`;`

## 例子
- 如果你想`保留`标题中包含`android`的文章，先把切换开关设置为`保留`。在文本框输入`android`即可
- 如果你想`保留`标题中包含`android`，同时含有`google`的文章，先把切换开关设置为`保留`。在文本框输入`android+google`即可
- 如果你想`保留`标题中包含`android`，同时含有`google`的文章 ，同时也想`保留`题中包含`chrome`的文章，先把切换开关设置为`保留`。在文本框输入`android+google;chrome`即可
- 如果你想`过滤`标题中包含`android`的文章，先把切换开关设置为`过滤`。在文本框输入`android`即可
- 如果你想`过滤`标题中包含`android`，同时含有`google`的文章，先把切换开关设置为`过滤`。在文本框输入`android+google`即可
- 如果你想`过滤`标题中包含`android`，同时含有`google`的文章 ，同时也想`过滤`标题中包含`chrome`的文章，先把切换开关设置为`过滤` 。在文本框输入`android+google;chrome`即可
