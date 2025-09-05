# Sync
### Q:Automatic synchronization does not work.
A:Please try to search "Battery Optimization" in system settings and set FeedMe as "Unoptimized". <a href="#qmore-tips-about-keep-feedme-alive">More tips</a>

### Q:Can I sync read items?
A:No, FeedMe only sync unread items from RSS service provider.

### Q:Can I sync portion feeds?
A:Yes, you can customize which feeds to sync here: `feed list` -> `Subscription`. And you can also customize whether to download the images, whether to download the full text, whether to display image title.

### Q:Why not show the full text/images even if I set up download full text/images?
A:Network problems are likely to occur during the synchronization process, resulting in the termination of the synchronization.

### Q:I don't see any news, what's going on?
A:It may be a problem, you can try clearing the cache, and then re-sync.

### Q: Difference between `Sync` and `Refresh`.
A:`Sync` will synchronize all you feeds, and including download images and web pages. But `Refresh` just trigger by pull down the article list. So it just synchronize the current category/feed. Of course if the current list is all items, it will synchronize all your feeds. And `Refresh` won't download images and web pages.

# Subscribe
### Q:Where can I add new subscription?
A:You can find a subscribe menu in `feed list` -> `Subscription`. And then you can search feed by title or url.

# View
### Q:Why are the articles that I have read gone? And be deleted?
A:By default, FeedMe will hide articles that have been read. You can switch the display of `unread articles` and `all articles` through the `⭕️` icon in the article list page.

And this change also effect side bar. If switch to `unread articles`, only the feeds which have unread articles will show. If switch to `all articles`, all feeds will show at side bar.

### Q:How can I enable split action bar & side navigation bar?
A:You can enable them in `Settings` -> `Control`.

### Q:How to see one feed only, not whole category?
A:Tap arrow icon, it will show all feeds.

### Q:Can't find the sort option of article list.
A:Article list -> view menu(eye icon) on action bar -> order.

### Q:Can't show thumbnails, but if open article and back, thumbnails show, why?
A:Because InoReader does not support thumbnails for 3rd party app, but Feedly supports. After download images for one article, FeedMe will select one image as thumbnail for InoReader account. So you can't get thumbnail, but once open article, FeedMe downloads all images, and thumbnail can show when back to list.
 
Another tip, if images downloaded when aotu sync, the thumbnail can show without opening article first. 

# TTS
### Q:TTS player stop after screen lock or FeedMe is not at foreground.
A:Please try to search "Battery Optimization" in system settings and set both FeedMe and the using TTS engine as "Unoptimized". <a href="#qmore-tips-about-keep-feedme-alive">More tips</a>

# Others
### Q:More tips about keep FeedMe alive.
A:[https://dontkillmyapp.com/](https://dontkillmyapp.com/)

### Q:What does `keep unread` mean?
A:`keep unread` just keep unread locally, will not be synchronized to the server. If you clear cache, logout or reinstall the application, you will not be able to retrieve records which keep unread. So temporary use keep unread only.

### Q:How to save to Pocket, Evernote, Instapaper, Readability?
A:You need enale the service which you want in `Settings` -> `Services` first.

### Q:Can I use the volume keys to navigate?
A:Yes, you can enable it in `Settings` -> `Control`.

### Q:I use right hand for single-hand operation, swipe return and side navigation are inconvenient.
A:You can try to disable `One-Hand Operation` in `Settings` -> `Control`.

### Q:Will FeedMe consume a lot of traffic?
A:By default, all automatic network operations will be carried out under wifi network. You can find the related settings in `Settings` -> `Sync` -> `Traffic`.

### Q:Can other RSS services or other AI APIs be supported?
A:Since I have a full-time job and limited spare time, I don't want to spend too much time adding and maintaining RSS services and AI APIs, so I have the open source project [FeedUs](https://github.com/seazon/FeedUs). FeedMe's RSS / AI feature is coming from here. You can add the new RSS services / AI APIs support and create a PR. I will verify it and merge the code. And then support in FeedMe.
- RSS service: Implement [RssApi](https://github.com/seazon/FeedUs/blob/main/lib/src/commonMain/kotlin/com/seazon/feedme/lib/rss/service/RssApi.kt) and refer to the completed RSS service implementation in this [directory](https://github.com/seazon/FeedUs/tree/main/lib/src/commonMain/kotlin/com/seazon/feedme/lib/rss/service).
- AI: Just implement a class similar to [GeminiApi.kt](https://github.com/seazon/FeedUs/blob/main/lib/src/commonMain/kotlin/com/seazon/feedme/lib/ai/gemini/GeminiApi.kt).
