# 1.10 2015-10-23  2015-10-26
- Support in-app browser.
- Support open youtube video in Youtube app.
- New mobilizer: Embedly.
- Improve article style (Audio and A tag).

###### 1.9.2 2015-8-12
- Remember positon of last article.
- Improve volume buttons navigation.

###### 1.9.1 2015-6-30
- InoReader, BazQux, The Old Reader support subscribe. (If you use The Old Reader, you can not specify which category added to yet)
- Support proxy (Android 2.3+, Settings -> Sync).
- Update Polish, Japanese, German, Spanish.

# 1.9 2015-6-10  2015-6-12
- Support The Old Reader.
- New option 'Horizontal Scrolling' under settings -> ui.
- Optimize synchronization speed and reduce the data traffic.
- Optimize mobilizer garbage problem.
- Optimize for metered WiFi network, won't automatic synchronize if set WiFi only.
- Different size of content request depending on the network.
- Starred items upper limit to 100.
- Starred items always download the full text.
- Optimize login failed error message.

###### 1.8.9 2015-5-13
- Support BazQux Reader.
- Support new InoReader developer portal.
- Show images which in enclosure tag for InoReader.

###### 1.8.8 2015-4-27
- Fixed issue: Can't add feed in some case.
- Fixed issue: Volume keys flipping more accurate.

###### 1.8.7 2015-4-13
- New option: Auto sync when charging only.

###### 1.8.6 2015-3-13
- Fixed issue: FC on Android 2.2/2.3.

###### 1.8.5 2015-3-12
- Fixed issue: can't change Feedly account after logout.
- Fixed issue: can't remember cache location.

###### 1.8.4 2015-3-3
- Add hardware acceleration option, disable by default.
- Now video open in a new window.
- Fixed share by instapaper issue.

###### 1.8.3 2015-2-12
- Fixed FC issue when opening image page or zooming image.
- Fixed FC issue when reading article.

###### 1.8.2 2015-2-9
- Fixed Inoreader sync a little items issue.
- Fixed Feedly sync failed in some case issue.

###### 1.8.1 2015-2-1
- Custom cache location.
- Fixed action bar in selection mode in article page.
- Fixed keep unread and starred items change to unread issue.
- Fixed FeedMe molibizer can't download images issue.

# 1.8 2014-12-19 2015-1-13 2015-1-18
- Support InoReader. (Not support search feed and subscribe in FeedMe)
- Backup and restore program settings and subscription settings.
- Now you can choose SD card as cache location.
- Now error log will be recorded here:/sdcard/Android/data/com.seazon.feedme/files/logs/error.log
- Pictures saved position change to /sdcard/feedme/pictures.
- Update Polish, Romanian.
- Other minor changes and bug fixes.

###### 1.7.3-1.7.4  2014-11-2 2014-11-25
- Support online video (YouTube, youku) in articles page.
- Edge To Edge image.
- Fixed unsubscribe from article list page or article page always show loading dialog.

###### 1.7.2 2014-10-23
- Support Persian, Ukrainian, optimized for RTL language.
- In addition to the system language and English, now you can choose other already supported languages.
- Notification sound and vibrate base on system setting. Auto sync always silent.
- Fixed article list FC issue.
- Fixed image title can't display issue.
- Fixed can not scroll in some dialogs.

###### 1.7.1 2014-9-15
- Fixed web page can't display issue.
- Fixed android 2.2 and android L connection issue.
- Other minor updates.

# 1.7 2014-9-14
- The new built-in image viewer, support GIF.
- Support favicon, you can get in Settings -> Cache.
- The new theme for E Ink screen.
- Optimized global return, now you can disable it in Settings -> Control.
- Optimized page. (display playback and download if page contains audio, the head space)
- Provide copy to Clipboard menu when long press link.
- Adjust nav drawer width, according to the width of your phone.
- Updated German
- Fixed last updated time not change in some cases.
- Fixed wrong position issue when return to article list.
- Fixed system font size setting not work when using English language.
- Fixed icon color of dialog box when long press in article page.
- Fixed some FC issues.

# 1.6 2014-7-22
- Bottom actionbar come back.
- Add a new option `One-Hand Operation`, to configure swipe back feature from left side or right side, also for displaying side navigation bar at left or right.
- Add a new option `Double Touch`, to configure the behavior when double touch on the article page.
- Support dashclock extension.
- New simple help page(Settings -> About).
- Support Polish, update Romanian and French.
- Improve swipe back feature, now you can swipe back(swipe from right side) in each screen.
- Add an option `0` for `Items to Keep`, for removing all read articles in local.
- Add transitions.
- New unified dialog style.
- Improve article blockquote style.
- Improve immersive mode, now you can scroll up/down to hidden/show system UI, also support single tap.
- Fixed still consume traffic in article page when set wifi only issue.
- Fixed tap image and open browser issue.
- Fixed subscrib failed issue.

###### 1.5.5 2014-6-2
- Support image title in article page. Default not show, you can enable it in `Subscription`. (Note that this only works on new articles, synchronized articles won't work)
- Add feed subscription dialog in article list page and article page.
- Improve Instapaper mobilizer.
- Improve article format: improve code display, support strikethrough, fix word break issue. (Note that this only works on new articles, synchronized articles won't work)
- Update Spanish, Russian.
- Fixed landscape mode not work issue.

###### 1.5.4 2014-5-26
- Support swipe right to back in article page(Beta).
- Recover article page render.
- Fixed read, star menu icon issue.

###### 1.5.3 2014-5-22
- Minor modifications of user interface.
- Fixed flashing/blink issue in article page on Android 4.0.
- Fixed issue: tapping up button in article page , takes back to subscription list instead of article list.

###### 1.5.2 2014-5-12
- Display feed list first when launch app.
- Read/unread, starred/unstarred setting back to 1.4.0.
- Won't show pacman gif when loading web page from feed page.
- Fixed error image share action in article page.
- Fixed splash issue in notification bar.
- Fixed FC issue.

###### 1.5.1 2014-4-29
- Fix immersive mode issue.

# 1.5 2014-4-27
- Important, please clear the cache and resynchronization. The new version changed the cache location to external storage under Android/data/com.seazon.feeme/
- Support Navigation Drawer.
- Support Full-screen Immersive mode for 4.4+.
- Support Preference Headers for 3.0+.
- Move synchronization progress to notification bar.
- Sync on app launch.
- `Days to Keep` change to `Items to Keep`.
- Add scroller option for volume navigation.
- Fixed can't share image in image page.

# v1.4 2014-1-16
- Now you can switch display language between system default and English.
- Optimize left and right margins on article page for some device.
- Now volume buttons show next/prev page, not next/prev article.
- Tap link in article will open browser directly, long press to show more options.
- Now subscription and sync manager in one page, and you can set sync detail there.
- Accessibility improvements on article page.
- Bug fixed: Force close when sync.

###### v1.3.9 2013-12-12
- Bug fixed: Picture can not zoom in android 4.4

###### v1.3.8 2013-12-11
- Support German.
- Add more options for Days to Sync and Days to Keep.
- Bug fixed: Some websites show html code in web view with FeedMe mobilizer.
- Bug fixed: Title shows html code.

###### v1.3.7 2013-10-24
- Support Korean.
- Improvement: Notification will be displayed only when the unread items is greater than 0.
- Bug fixed: Some websites show garbled characters in web view with FeedMe mobilizer.
- Bug fixed: URL can not subscribe.
- Bug fixed: Starred items not remove when Starred List set to 0.

###### v1.3.6 2013-10-11
- Support Italian.
- Display feed name when unsubscribe a feed.
- fixed can't switch to all items and other related issues.

###### v1.3.5 2013-10-8
- Improvement: Add a option for notification when sync finish.
- Improvement: Add a option for mobilizer engine.
- Improvement: Hide feed when count is 0.
- Improvement: Hidden bottom bar when scroll article.
- Improvement: Show in browser will also mark that item as read.
- Bug fixed: Mark previous read marks more items as read.

###### v1.3.4 2013-9-30
- Default using safe mode for China.
- Fixed can't download web page.

###### v1.3.3 2013-9-25
- Fixed FC bug.

###### v1.3.2 2013-9-25
- Fixed can't login bug.

###### v1.3.1 2013-9-24
- Add a option to enable HTTPS.

# v1.3 2013-9-24
- Support one tap save to Pocket, Instapaper, Readability and Evernote.
- Now you can switch between feed view, web view and open in browser more easily, There is a view switch bar in the bottom of article page. And you can change web view(mobilizer view) via long press the second button.
- Use HTTPS connection.
- Add a option to keep the action bar.
- Add a option to just sync images.
- Uncategorized feeds back to top level.
- Fixed tag sync issue.
- Fixed garbled characters in web view(mobilizer view).
- Fixed can not open the starred articles of unsubscribed feeds.

###### v1.2.3
- Support Romanian.
- Fixed can not manually synchronize issue. Now manual synchronization can work all the time. For automatic synchronization, it won't work while battery lower than 20% and not charging.
- Fixed other issues.

###### v1.2.2
- Expand uncategorized by default if no category.
- Fixed FC issue when open subscription page.

###### v1.2.1
- New subscription page, support subscribe and unsubscribe.
- Add `Reload page` menu in article page.
- Fixed sync nothing(only starred items) issue.
- Fixed other issues.

# v1.2
- Support swip left and right in article list page.
- Stop auto synchronization when battery less than 30%.
- Fixed feedme mobilizer garbled text.
- Fixed some small issues.

# v1.1
- Support volume buttons navigation.
- Support unread count widget.
- Support toggle between all items and only unread in article list page.
- Remove `Mark previous as read` menu in starred article list page.
- Fixed marking read failed items still display as unread after sync.
- Fixed mark all as read and back to home page, the number not update.
- Fixed mark read error when order by oldest.

###### v1.0.5
- Support subcribe.
- Support French.
- Support tapping title in article page to open browser.
- Improve web view.
- Fixed small issues.

###### v1.0.4
- Disable show action bar when scroll down.
- Fixed web page can't download issue.

###### v1.0.3
- Support Brazilian Portuguese.
- Support tap Menu button to show more menu.
- Night theme is back.
- Improve starred items order.
- Improve scroll in article view.
- Fixed some small issues.
- Fixed logout and relogin with the old account issue.
- Fixed can't unstar issue
- Fixed image name issue with `;charset=utf-8`.

###### v1.0.2
- Fixed save to Pocket & Instapapter issue.

###### v1.0.1
- Fixed can't order by oldest issue.
- Fixed web view of articles doesn't work issue.

# v1.0 13-06-20
- Change RSS service from Google Reader to Feedly.
- Add Readability mobilizer.
- Hidden nav bar in article page for 4.0+.
- Update Spanish, Chinese.
- Remove READ_LOGS permission.
- Improve Pocket sharing.
- Improve action bar.
- Fixed page background issue.
- Fixed several crashes.
