### 3.20.14
###### 2022-7-10
- [fix]Fix theme follow system not work issue.

### 3.20.13
###### 2022-7-10
- [fix]Fix some options lost in `Integrations`.

### 3.20.12
###### 2022-7-3
- [fix]Fix can't share to WeChat issue.
- [fix]Fix the issue that some options lost when long-pressing the text on the article page.

### 3.20.11
###### 2022-6-28
- [optimize]Update French, Polish, German.

### 3.20.10
###### 2022-6-14
- [fix]https://github.com/seazon/FeedMe/issues/435
- [fix]TTS can't play issue.

### 3.20.9
###### 2022-5-28
- [fix]Fix crash issue on article page.

### 3.20.8
###### 2022-5-28
- [optimize]https://github.com/seazon/FeedMe/issues/420
- [fix]https://github.com/seazon/FeedMe/issues/426

### 3.20.7
###### 2022-4-1
- [optimize]Improve figcaption tag style. https://github.com/seazon/FeedMe/issues/403
- [optimize]Ethernet connection should same as Wifi. https://github.com/seazon/FeedMe/issues/400

### 3.20.6
###### 2022-3-12
- [fix]Crash issue in article page on Android 12.

### 3.20.5
###### 2022-1-21
- [fix]Some iframe embedded video can play https://github.com/seazon/FeedMe/issues/392
- [fix]Improve RTL language display in article page https://github.com/seazon/FeedMe/issues/391

### 3.20.4
###### 2022-1-14
- [fix]Fix status bar theme issue on Android 12+.

### 3.20.3
###### 2022-1-2
- [fix]Fix status bar height issue on Android 12+.
- [fix]Fix custom launcher crash issue when using image.

### 3.20.2
###### 2021-12-24
- [fix]Fix crash issue on Android 12 https://github.com/seazon/FeedMe/issues/385

### 3.20.1
###### 2021-12-23
- [optimize]Adapt for Android 12.
- [optimize]Update Hebrew, German, French, Dutch, Spanish, Italian, Ukrainian, Portuguese (Brazil), Romanian, Czech.
- [fix]https://github.com/seazon/FeedMe/issues/382

# 3.20.0
###### 2021-11-1
- [new]Support dark mode for Android 10+.
- [new]Support OPML import and export.
- [optimize]Remove `Manual Refresh` in settings, update manual refresh logic.
  - Refresh list if list never scroll when sync done.
  - Otherwise, if new items fetched for current list, show manual refresh tips.
- [optimize]Hide `New` button in `Add tag` dialog for Tiny Tiny RSS, and fix https://github.com/seazon/FeedMe/issues/369
- [optimize]Clear feed when logout.

### 3.19.3
###### 2021-10-19
- [fix]Fix scroll bar disappear in article page.
- [fix]Fix RSS link and date parse issue.
- [fix]https://github.com/seazon/FeedMe/issues/365
- [fix]https://github.com/seazon/FeedMe/issues/366
- [fix]Fix save blank favicon in some cases.

### 3.19.2
###### 2021-9-15
- [optimize]Favicon supports SVG.
- [fix]https://github.com/seazon/FeedMe/issues/330

### 3.19.1
###### 2021-9-11
- [fix]Fix images cannot be displayed.

# 3.19.0
###### 2021-9-9
- [new]Support long lick to select text on article page to add highlighter.
- [optimize]Show amount of highlighter on side bar.
- [optimize]Increased the number of highlighter on sidebars to 10.
- [fix]Fix https://github.com/seazon/FeedMe/issues/342
- [fix]Fix https://github.com/seazon/FeedMe/issues/354

### 3.18.3
###### 2021-6-10
- [fix]Fix purchase refund issue.

### 3.18.2
###### 2021-6-6
- [fix]Fix small issues.

### 3.18.1
###### 2021-5-3
- [optimize]New Language: Hebrew. Update French, Spanish, German, Czech, Hungarian, Dutch.
- [fix]Fix https://github.com/seazon/FeedMe/issues/301
- [fix]Fix https://github.com/seazon/FeedMe/issues/308
- [fix]Fix https://github.com/seazon/FeedMe/issues/311
- [fix]Fix other issues.

# 3.18.0
###### 2021-3-19
- [optimize]Improve load favicon logic and support reload favicon and move the `unsubscribe` button place in feed manager dialog. https://github.com/seazon/FeedMe/issues/286
- [optimize]`Open in browser` can apply to category or feed.
- [optimize]`Show image alt` apply to global
- [optimize]New Language: Slovak, Arabic, improve R2L layout. Update Japanese, German, Spanish, Italian, Dutch, Ukrainian.
- [optimize]Built-in browser support dark mode which require `Android System WebView` as WebView implementation. Improve the top and bottom padding issue.
- [optimize]Merge rss url and keyword in explore, improve rss parser.
- [optimize]Add more playback speed.
- [fix]Fix synchronization interruption issue. https://github.com/seazon/FeedMe/issues/297
- [fix]Fix stop sync if 0 unread at server side. https://github.com/seazon/FeedMe/issues/284
- [fix]Fix scroll jump down issue when use 2 fingers.

### 3.17.4
###### 2021-2-8
- [fix]Fix TTRSS can't sync issue.
- [fix]Fix summary display issue.

### 3.17.3
###### 2021-1-31
- [optimize]Swipe keep unread again can update to read.
- [fix]Fix TTRSS can't unsubscribe feed issue.
- [fix]Fix HTML blockquote can't display issue.
- [fix]Fix time parse issue in show note page.
- [fix]Fix widget not update count issue.

### 3.17.2
###### 2021-1-23
- [fix]Apply theme for blocking image.
- [fix]Fix FeedMe mobilizer can't show image in some cases.

### 3.17.1
###### 2020-10-1
- [optimize]Add new option in `Setting`-`Interface`-`Highlighter`: Show `Highlighter` in NAV side.
- [optimize]Highlighter add `case sensitive` option.
- [fix]Fix crash issue which caused by `Highlighter` feature. https://github.com/seazon/FeedMe/issues/244

# 3.17
###### 2020-9-20
- [new]Highlighter https://github.com/seazon/FeedMe/blob/master/doc/en/highlighter.md
- [new]support jump/seek via time in show notes.
- [optimize]Reduce the space between paragraphs of article page.
- [optimize]The images in the `New List` layout have more display space.
- [optimize]Show refresh at bottom if enable `Split Action Bar`.
- [optimize]Update translation: Japanese, Dutch, German, Spanish.
- [fix]Fix FeedMe mobilizer failed in some case.
- [fix]Fix show read time as 1 min. https://github.com/seazon/FeedMe/issues/223
- [fix]Fix play note screen not show note issue.
- [others]Remove phone permission.
- [others]Update IAB and other 3rd party libraries.

# 3.16
###### 2020-6-21
- [new]New custom fonts, no longer rely on font packages. Old font package is no longer compatible.
- [fix]When searching for podcasts and episodes, due to third-party interface restrictions, you cannot directly subscribe, so now open the browser to obtain the subscription url.
- [fix]https://github.com/seazon/FeedMe/issues/209
- [fix]https://github.com/seazon/FeedMe/issues/202
- [other]Call player command via 3rd party app.
``` java
Intent intent = new Intent();
intent.setAction("com.seazon.feedme.action.STOP_ACTION");
sendBroadcast(intent);

// actions:
com.seazon.feedme.action.PLAY_ACTION
com.seazon.feedme.action.STOP_ACTION
com.seazon.feedme.action.NEXT_ACTION
com.seazon.feedme.action.PREVIOUS_ACTION
com.seazon.feedme.action.FORWARD_ACTION
com.seazon.feedme.action.REPLAY_ACTION
com.seazon.feedme.action.STAR_ACTION
```

### 3.15.2
###### 2020-6-4
- [optimize]Update Polish，Italian，Norwegian, Spanish, Dutch，German.
- [fix]Fix the problem that TTS will not continue to play in some cases.
- [fix]FreshRss supports synchronization by feed/category.
- [fix]Fix other issues.

### 3.15.1
###### 2020-5-16
- [optimize]Identify 5G networks.
- [fix]Fix icon display issue.
- [fix]Fix other issues.

# 3.15
###### 2020-5-5
- [new]Add explore at sidebar, supports search podcast.
- [optimize]Inoreader(not OAuth), TheOldReader, Bazqux support modify host in login page.
- [optimize]Show podcast indicator in article list page.
- [optimize]Icon adapter with theme color.
- [optimize]Remember expand status of twitter layout.
- [other]Allow user certificate.

### 3.14.1
###### 2020-4-5
- [optimize]Update Czech, Italian, Indonesian, German, Hungarian, Polish, Spanish.
- [optimize]Update next/previous to forward/replay in notification.
- [fix]Fix scroll issue of article screen.
- [fix]Fix feed search issue.

# 3.14
###### 2020-4-2
- [new]New layout: Twitter.
  - For short content
  - Show full text and picture in list
  - No need to enter article screen
- [optimize]Optimize the connection of Feedly.
- [optimize]optimize layout of article screen for tablet.
- [optimize]Adjust the color of paper and dark themes to improve readability.

# 3.13
###### 2020-2-4
- [optimize] Compatible with Android 10 storage mechanism, please see <a href="https://github.com/seazon/FeedMe/blob/master/doc/en/storage_and_cache.md">Storage and Cache</a>
- [optimize] Optimize the function of blocking images, please see <a href="https://github.com/seazon/FeedMe/blob/master/doc/en/block_image.md">Blocking Images</a>
- [optimize] Enable `Decode HTML` by default.
- [fix] Fix the problem of opening wrong image in the article screen.
- [other] The minimum supported version is increased to Android 5.

### 3.12.4
###### 2020-1-3
- [optimize]`Decode HTML` adds a global default value(in settings - sync - advanced).
- [fix]Fix sync failed issue.

### 3.12.3
###### 2019-12-30
- [optimize]Support add feed url directly.
- [optimize]Optimize HTML pre tag style.
- [optimize]Add `Decode HTML` open in feed settings dialog, for some encoded HTML page. Default is off.
- [optimize]`Auto sync on Wi-Fi only` in `Traffic` enable now when disable `Auto Sync` but enable `Sync on app launch`.
- [fix]Fix the problem of new articles not displaying after synchronization.

### 3.12.2
###### 2019-11-19
- [new]Support Feedbin parser for mobilizer.
- [fix]Fix backup failed issue.
- [fix]Fix article date issue of Fever.

### 3.12.1
###### 2019-10-15
- [optimize]The article's image can now be aligned with the article. This setting can be found in the `View` menu of the article screen.
- [optimize]Optimize 'manual refresh'. Now you can disable it in the 'sync' setting.
- [optimize]Fever displays a tip in the login dialog.
- [optimize]Update German，Italian，Dutch，Spanish.

# 3.12
###### 2019-9-28
- [new]Support sharing to WeChat friends.
- [new]Support Norwegian.
- [optimize]The article list won't refresh when synchronization is done if you stay on this screen. Instead, a popup will appear at the top.
- [optimize]Update Italian.
- [fix]Fix an issue that failed to share to WeChat moment.

# 3.11
###### 2019-9-15
- [optimize]`Write external storage` permission is not enforced when launch app, but request when need.
- [fix]Fix TTS reading characters incorrectly issue.

### 3.10.6
###### 2019-9-4
- [fix]Fix `Sync on app launch` not work if set `Sync Interval` as `Never`.

### 3.10.5
###### 2019-8-18
- [fix]Fix crash issue when using `Card` layout.

### 3.10.4
###### 2019-8-13
- [fix]Reduce too much automatic synchronization.

### 3.10.3
###### 2019-7-22
- [fix]Fix delay issue when opening articles.

### 3.10.2
###### 2019-7-20
- [new]Support Fever.
- [fix]Fix Feedbin sync issue.
- [fix]Remove Mercury.

### 3.10.1
###### 2019-6-8
- [optimize]TTS supports media button next/previous (single click to replay/forward, double click to next/previous article).
- [fix]Fixed crash issue on Android 4.x~6.x.
- [fix]Fixed language setting issue.

# 3.10
###### 2019-5-30
- [optimize]Optimize automatic synchronization.
- [optimize]If disable downloading full text and image of all feeds, skip the relevant synchronization process.
- [optimize]Optimize the article list feed name display, now it will display as much as possible.
- [fix]Now built-in image browser is the default.
- [fix]Fixed TTS issue when web page has been downloaded.
- [fix]Clearing the cache no longer clears the feed sorting data.
- [fix]Fixed failed to get modified tag name on Feedly.

### 3.9.4
###### 2019-4-27
- [new]Support custom share template, find it in new setting category `Individuation`.
- [optimize]Article summary text from 144 to 200, to avoid incomplete display.
- [optimize]Update cs, de, es, it, nl, pl, pt-br, ro, uk, zh-tw.
- [fix]Fix custom launcher can't add picture error.

### 3.9.3
###### 2019-3-20
- [fix]Fix crash issue on Android 4.x.

### 3.9.2
###### 2019-3-16
- [optimize]Optimize sorting: Provide reset button. Uncategorized feeds can also be sorted.
- [fix]Fix login and built-in browser issues on Android 9.
- [fix]Fix crashes when searching and adding subscriptions.

### 3.9.1
###### 2019-3-14
- [optimize] Remove Umeng analysis.
- [fix] Feedly, Inoreader now only support HTTPS.
- [fix] Now sorted alphabetically by default. `Reset order` menu will be added in next version.
- [fix] Fixed Tiny Tiny RSS can't save image issue.
- [fix] Fixed unplugging headphones and not stopping playing issue.

# 3.9
###### 2018-10-6
- [new] Feed supports sorting.
- [optimize] Add sd card path in cache path if SD exists.
- [optimize] Update media while save picture, then this picture can show in gallery or other image browsers. (Some devices not support)
- [fix] Tiny Tiny RSS supports attachments.
- [fix] Fixed InoReader / FreshRSS / The Old Reader / Bazqux tag display issue.

### 3.8.5
###### 2018-8-8
- [new] Support BlackBerry key series quick actions through keyboard. Link: https://github.com/seazon/FeedMe/blob/master/doc/en/shortcut_key.md
- [optimize] Add a text description to the upper right sidebar and back button to make it easier for people with poor eyesight.
- [fix] Fixed an issue where FeedMe mobilizer could not parse pure audio pages correctly.
- [fix] Fixed an issue where images could not be downloaded under WIFI in some cases.

### 3.8.4
###### 2018-7-8
- [new] Add `Data Collection` option in `Settings` - `About `, default is disabled.
- [fix] Fix image duplication issue of Mercury mobilizer.

### 3.8.3
###### 2018-7-7
- [optimize] Mobilizer displays the reason when fetching article fails, and providing `report issue` at bottom.
- [optimize] Mercury supports display header image.
- [optimize] Now FeedMe is the same as the official Feedly client, and thumbnails will appear in article page.
- [fix] Fix invisible issue of `Unsubscribe` and `Filter` in `Feed Management Dialog`.
- [fix] Fix parsing issue of HTML.
- [fix] Now the content obtained by Tiny Tiny RSS is sorted by time.

### 3.8.2
###### 2018-6-23
- [fix] Fix automatic synchronization does not work issue.
- [fix] Fix `keep unread` status reset issue.
- [fix] Fix other issues.

### 3.8.1
###### 2018-6-21
- [fix] Fix crash issue and some other issues.

# 3.8
###### 2018-6-15
- [new] Support podcast chapters.
- [new] Support adaptive icon.
- [new] `Auto Switch Night Mode` supports custom time.
- [optimize] Optimize the speed of syncing unread articles.
- [optimize] Optimize sharing to WeChat Moments, support sharing podcasts.
- [optimize] Upadte Dutch, Chinese Traditional, Spanish, German, Romanian, Czech, Russian, Portuguese (Brazil), Hungarian.
- [fix] Fix other issues.

### 3.7.1
###### 2018-5-24
- [fix] Fix crash issue.

# 3.7
###### 2018-5-23
- [new] Support share to WeChat Moments, enable in `Settings` - `Integrations`.
- [optimize] New option `Playback Speed` in `Setting` - `Audio`, disable this if TTS not work.
- [fix] Fix some devices can't install from Play store.
- [fix] Fix missing spaces between words in article page.
- [fix] Fix missing subject when sharing email in some cases.

# 3.6
###### 2018-4-28
- [new] Only for supporters: Create custom launcher icon in `Setting` - `About`.
- [optimize] New optioin in `Setting` - `Interface`: Always show the NAV side when the screen is wide enough.
- [fix] Fix cache number replacement issue.
- [fix] Fix "open url failed" issue.
- [fix] Fix other issues.

### 3.5.9
###### 2018-4-21
- [ATTENTION] Requests CAMERA and SHORTCUT permission to support new shortcut feature, but not available in this version.
- [fix] Fix sync button and item count not show in NAV side on small phone.

### 3.5.8
###### 2018-4-12
- [new] Highlights NAV side item for current list.
- [new] Play page adds star menu.
- [fix] Fix a problem where the title of the article list did not change when switched NAV side item.
- [fix] Fix a problem of missing temporary tags.

### 3.5.7
###### 2018-4-4
- [new] When the screen width exceeds 640dp, the first screen displays both article list and the sidebar. (Android 7.1+ devices with virtual navigation bar will have display problems when rotating horizontal screen clockwise)
- [new] Support Bluetooth headset (play and stop).
- [new] `Image Browser` Add `Disable` option.
- [new] Feedbin supports self-hosted.
- [optimize] Pull down refresh always synchronizes the current list, not whole. If the current list is `all items`, it is similar to the overall synchronization.
- [optimize] Optimize the FreshRSS login experience and automatically complete the API address.
- [optimize] Optimize one-tap sharing to Todoist in article page.
- [optimize] `Temporary tag` limit raised to 5.
- [fix] Fix false navigation position determination on Android 7.1+ devices.
- [fix] Fix the problem that login information is not recorded when logging in for the first time (problems arise from 3.5.6).
- [fix] Fix `Synchronous Mode` is set to `All`, but with certain feeds disabled, the number of syncs is abnormally wrong.
- [fix] Fix the issue where FreshRSS only syncs 100 items (problems arise from 3.5.6).
- [fix] Fix issue with using TTS playback exceptions in certain situations.

### 3.5.6
###### 2018-3-14
- [ATTENTION] Due to changes in the multi-account feature, downloaded images will not be visible after updating to the new version. If need, clear the cache and download it again.
- [optimize] Services(Feedbin, FreshRSS) that do not support feeds/categories synchronization can't modify `Sync Mode` now. `Chinese Mode` is also the same. `Sync Mode` is fixed to `All`.
- [optimize] Tiny Tiny RSS now support auth_remote.
- [fix] Fix too many articles marked as read when enable `Auto mark read`
- [fix] Fix FeedMe mobilizer parsing webpage garbled.
- [fix] Keyword filtering now ignores case.
- [fix] Fix other issues.
- [other] Changes related to multi-account feature.

### 3.5.5
###### 2018-2-24
- [optimize] If there is a notification during audio playback, the playback will not be paused, but the volume will be reduced.
- [optimize] Download process shows the number of downloaded images.
- [fix] Fix for `Json parse error` when Feedly sync.
- [fix] Fix synchronization stuck issue of Tiny Tiny RSS when pull to refresh.
- [fix] Fix TTS 2 word read into a word problem.
- [fix] Fix a problem with untranslated text of list summary.
- [other] Call sync service via 3rd party app.
``` java
Intent intent = new Intent();
intent.setClassName("com.seazon.feedme", "com.seazon.feedme.sync.service.SyncService");
intent.putExtra("auto", false);
intent.putExtra("type", syncTypes);
activity.startService(intent);

// syncTypes is following (add value to do more than one action):
public static int SYNC_TO_SERVER = 1;
public static int SYNC_UNREAD_FROM_SERVER = 2;
public static int SYNC_STARRED_FROM_SERVER = 4;
public static int SYNC_DELETE_READ = 16;
public static int SYNC_DOWNLOAD_IMAGE_AND_WEB_PAGE = 32;
public static int SYNC_DOWNLOAD_PODCAST = 256;
```

### 3.5.4
###### 2018-2-8
- [new] Support FreshRSS, a self-hosted RSS service like Tiny Tiny RSS. Site: https://freshrss.org/.
- [optimize] Now thumbnails can display even if not downloaded when syncing.
- [fix] Fix synchronization stuck issue of Tiny Tiny RSS.
- [fix] Fix crash issue when tap subscribe menu.
- [fix] Fix other issues.

### 3.5.3
###### 2018-1-29
- [optimize] Share link to FeedMe to subscribe. Or copy link to system clipboard, and fill automatically when click `Add subscription` menu.
- [optimize] Update French, German, Spanish, Russian, Italian, Czech, Portuguese (Brazil).
- [fix] Fix auth failed to Feedly via Evernote.
- [fix] Fix can't download images in some case.
- [fix] Fix duplicate menu issue.
- [fix] Fix other issues.
- [other] Add in-app goods: Cherry.

### 3.5.2
###### 2018-1-16
- [optimize] Update Chinese Traditional.
- [fix] Fix Tiny Tiny RSS can only fetch 100 unread issue.
- [fix] Fix article page can't show images after downloaded.
- [fix] Fix pull-down refresh synchronization could not mark server-read articles as read.

### 3.5.1
###### 2018-1-12
- [new] Add new `Favorites` notification besides `Sync` and `Play`, for showing the unread info of `temporary tag`. And now you can set `show notification if new items in` in feed setting dialog. If the setted feeds have new items, also will show info in `Favorites` notification.
- [new] Support Android 8.0 notification channel. You can set different ringtone or other settings in system notification setting.
- [optimize] Now `temporary tag` show unread item count.
- [optimize] Star and unread indicator move to left side. Reading time is also affected by the `Settings` - `Interface` - `Showing Reading Time`.
- [fix] Fix auto showing `Play` notification in some case.
- [fix] Fix crash issue when enable `Eink Improvement`
- [fix] Fix issues of Tiny Tiny RSS.
- [fix] Fix images do not display even download progress bar gone in article page.

# 3.5
###### 2017-12-06
- [new] Support Tiny Tiny RSS. IMPORTANT: Go to your TTRSS web site preferences and enable "Enable API access", click "save  configuration" button and then login in FeedMe.
- [new] `Temporary tag`: Show all items which title contains keyword in one place. You can create and access it in NAV side, just like a feed. Max temporary tag count: 3.
- [new] Batch export images: If you subscribe some feed which contains a lot of images, you need to download one by one before. But now you can download all images of one feed/category one-time. The download path is same to single downloading image.Once finished, the unread articles will be marked as read if unread, and read and synced articles will be deleted.
- [optimize] Now you can hide your RSS account info via tap RSS type label which above your account name.
- [optimize] Now built-in browser is always open built-in browser, not Chrome custom tab or others.

### 3.4.3
###### 2017-11-29
- [fix] Fix does not download images and web pages when sync in some cases.

### 3.4.2
###### 2017-11-20
- [fix] Fix sync interval can't change issue if language is German.

### 3.4.1
###### 2017-11-16
- [optimize] Upadte German, Spanish, Portuguese (Brazil), Korean, Russian, French, Hungarian.
- [fix] Fix some traffic settings does not work issue.
- [fix] Fix article page can't hide action bar when scrolling issue.

# 3.4
###### 2017-11-13
- [new] Reorganize the `sync` setting. Now you can set all Wi-Fi only options in `Traffic`. The global feed settings in `Advanced`.
- [optimize] Show RSS service and account in NAV side.
- [fix] Now svg images can be displayed correctly.
- [fix] Sensitive scrolling in immersive mode.
- [fix] The bottom action bar displayed incorrectly in some cases.
- [fix] The uninstalled one-tap sharing menu can't remove from action bar.

### 3.3.2
###### 2017-10-11
- [optimize] Improve one-tap sharing system share. Now no need to reload the menus.
- [fix] Fix DashClock issue.

### 3.3.1
###### 2017-9-15
- [fix] Fix crash issue.

# 3.3
###### 2017-9-14
- [new] Support add system share in article page menu, then one-tap to share to your frequently-used app. (enable share in `Setting` - `Integrations`, and then you can find it in article page menus. Now maybe you need reload the menus to show it.)
- [new] Support custom notifications.
- [new] Support play video directly in the article page (add `Video Preview` in `Lab`).
- [optimize] Support horizontal display in play page.
- [optimize] Audio won't automatically downloaded after audio is disabled.
- [optimize] Some other small optimization.
- [fix] Fix filtering does not filter for certain keyword issues.
- [fix] Fix FeedMe Mobilizer issue in some case.

### 3.2.1
###### 2017-6-17
- [fix]Fix Feedly login with Google auth error.
- [fix]Adapt to ultra-wide mobile phone, like S8.
- [fix]Mark item as read when open it in browser directly.

# 3.2
###### 2017-6-12
- [new]Now you can play the whole list with the new `play list` menu. (this option will clear the play list first, and the max is 100 articles.)
- [new]Support auto download podcast audio file while syncing. (download 60 minutes at least.)
- [new]Support playback speed.
- [new]Support forward/replay, and you can set time in settings.
- [new]Support play menus in article page.
- [new]Add `enable audio` option, for disable audio feature for some people who don't need this.
- [new]Add `Open in browser` option in `Settings` - `Interface`, for open item in browser directly.
- [optimize]Add `Reset` button in menu edit dialog.
- [optimize]`Card` layout supports hide summary.
- [optimize]Optimize play feature and display.
- [optimize]Add `connection close` option.
- [fix]Fix order of starred items issue.

### 3.1.3
###### 2017-6-8
- [fix]Fix read items back to unread issue.

### 3.1.2
###### 2017-5-20
- [optimize]Now single tap to keep unread in article page, not twice. Update the `keep unread` icon.
- [optimize]Tap feed url to copy it in feed setting page.
- [optimize]Add playback control label for TalkBack.
- [optimize]Add `Thumbnail` switch in `Lab` setting. (Just for testing)
- [fix]Fix can't login Inoreader with Google account.
- [fix]Fix article hard to read when enable `Eink Improvement`.

### 3.1.1
###### 2017-5-9
- [optimize]Optimize ignored thumbnail list, the same picture won't add to list.
- [optimize]Back button to exit app will hide the read items.
- [optimize]Downloading failed pictures due to network timeout will continue to be attempted at the next time.
- [fix]Fix Bazqux issue, and improve the authentication expiration prompt of re-login tips.
- [fix]If enable split action bar, the FAB menu does not show when horizontal screen.

# 3.1
###### 2017-4-28
- [new]Support media button on headset.
- [new]Support sleep timer(on play screen).
- [new]Add feed states(`Settings` - `About`), for better understanding of feeds.
  - Show 2 values of each feed:
    - Interest value `read + star * 2`: the higher the value, the more articles you see in this feed, the more interested you are.
    - Read percent `read / ( read + glance )`: the higher the percent, the more you are interested in this feed. The percent >= 90% will be displayed frist.
  - Tap feed to show all 5 value:
    - fetch: synced articles.
    - filter: filtered articles.
    - glance: use `mark previous read` or `mark all read`.
    - read: read in article page.
    - star: starred articles.
  - Filter menu to choose scope(`today`, `this week`, `this month`, `whole`), default is `today`.
- [new]Support Chrome custom tabs.
- [optimize]Improve layout. Remove `summary` layout. Now when you select `list` layout, you can set show thumbnail/summary or not.
- [optimize]Now you can change TTS, but need restart app.
- [optimize]Change mark read time:
  - Before: enter article and mark it read. Now: leave article and mark it read.
  - Before: swipe A to B and mark B read. Now: swipe A to B and mark A read.
- [optimize]Remove Embedly mobilizer.
- [optimize]Update Spanish, Dutch, French, German, Korean, Portuguese (Brazil).
- [fix]Fix hide thumbnail issue. You can add max 32 thumbnails. If continue add, remove the first set thumbnail.
- [fix]Fix default browser issue, add `built-in` option. Now `default` means system default browser. If the system default browser does not set, show select dialog.

### 3.0.4
###### 2017-4-9
- Add an option `Show Reading Time` in `Interface` setting to show reading time in article page, default is false.
- Update `Pull to Refresh` option in `Control`, add a new item `Hide read items and sync`.
- Now long press on article list item won't work in `Visioin` layout.
- Now thumbnails load faster, and gif just shows first frame.
- Play menus add to `Swipe Left(Right) to Right(Left)` options.
- Auto mark item as read when read article via TTS.
- Fix Bazqux sync issue.

### 3.0.3
###### 2017-4-6
- Add `Eink Improvement` in `Lab`.
- Now you can set specific browser for browser and image browser.
- Now `24 hours` of `Auto Sync` is a special processing interval option, it will only sync in midnight. Note that if it does not sync in midnight, it will be synchronized when the network is available. And next synchronization time is the next midnight.
- Thumbnails can be long press and marked as AD images, then this picture will no longer be a thumbnail. You can add up to 16 images for the AD image. If you continue to add, the first AD image will no longer be considered an AD image.
- Update some icons.

### 3.0.1
###### 2017-3-20
- Fix crash issue.

# 3.0
###### 2017-3-19
- Support podcast (not support `Feedbin`) and TTS. Please read <a href="https://github.com/seazon/FeedMe/blob/master/doc/en/podcast_tts.md">Podcast & TTS</a> for the detail.
- Provide reading time.
- Add `Podcast` layout, which show play or download progress.
- Add `Lab` in `Settings`, including `Hardware Acceleration`.
- Improve `Accent` color, now support more color and customize color.
