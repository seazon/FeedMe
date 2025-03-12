FeedMe支持TTS和播客，你可以听你喜欢的文章。

- 对于播客源，FeedMe支持手动下载来离线收听。
- 对于普通源，FeedMe支持标准Android TTS标准，你可以选择你喜爱的TTS引擎来播放，比如语记。

为简化表述，以下播客源的音频和普通源的文章都称为节目。

FeedMe整合了这2种不同形式，你可以像听音乐一样收听所有订阅的节目。

在左侧导航栏提供play栏目进入播放列表。为简化逻辑，feedme全局只有一个播放列表。右侧数字为列表内节目的数量。

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_2.png" width="25%" height="25%" />

为了方便播放，新增`播客`布局。它提供一个带有进度条的播放按钮，你可以用它来播放节目，或者下载播客源的节目。

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_8.png" width="25%" height="25%" /> <img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_9.png" width="25%" height="25%" />

# 播放控制
在文章列表页长按节目，提供多种播放菜单：
- `单个播放` （加入播放列表头，并在此节目上加上`停止标记`，播放此节目）
- `播放` (加入播放列表，如果当前正在播放，则停止当前播放的，在其前面插入所选节目并播放。如果当前未播放，插入到播放列表播放位置)
- `下一个播放` (加入播放列表，插入正在播放的节目后面)
- `添加到播放列表` (加入播放列表，插入到队列最后)

`停止标记`: 当播放完带有`停止标记`的节目后，就停止播放。播放列表中只有一个`停止标记`，并且播放完带有`停止标记`的节目后会清除`停止标记`。

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_1.png" width="25%" height="25%" />

# 播放列表
- 播放完的节目会在一定时间后自动删除音频文件，并从播放列表中移除。所以你不需要手动维护播放列表。如果你喜欢某个节目，将其加星就不会被删除，但这个节目会从播放列表移除。
- 每个节目都会记录播放位置，再次播放会从上次播放的位置开始。
- 播放列表中的节目可单条移除，向左滑移除。
- 第一版不支持在线播放，如果碰到没有下载的节目，则跳过。
- 播放列表仅支持单次顺序播放，没有单曲循环，循环播放、随机播放。
- 播放列表可以通过拖拽调节前后次序。
- 碰到已播放完的节目会自动跳过。

当一个节目播放时，通知栏会显示相应信息。你可以点击它来进入播放界面。

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_6.png" width="25%" height="25%" />

# 播放界面
播放界面有3个子页面。你可以看到在播放列表界面有一个`停止标记`。

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_3.png" width="25%" height="25%" /> <img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_4.png" width="25%" height="25%" /> <img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_5.png" width="25%" height="25%" />

# TTS设置
`设置`中增加了`音频`标签，你可以在此进行相关设置。

<img src="https://github.com/seazon/FeedMe/blob/main/doc/en/imgs/tts_7.png" width="25%" height="25%" />

# 提示
### 播放feed页面还是web页面
##### Q: 有时订阅源没有输出全文，此时如果将页面切换到web页面后播放，它仍会播放feed页面的内容。那么应该如何播放web页面的内容呢？
A: 你可以阅读<a href="https://github.com/seazon/FeedMe/blob/main/doc/zh/mobilizer.md#默认显示">这个部分</a>。
