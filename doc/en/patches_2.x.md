###### 2.6.2 2017-3-2
- Support dir tag of HTML.
- Add "Mark Read Action" option in Interface setting.
- Improve feed manager dialog.
- Update French, Dutch, Hungarian, German, Spanish, Russian, Chinese Traditional, Czech.
- Fixed custom action bar error icons and text issues.
- Fixed incomplete count of article page issue.
- Fixed repeat loadig issue of built-in browser.

###### 2.6.1 2017-1-23
- Add new option to Pull to Refresh: Hide read items.
- Mark all read now auto open the next category/feed. If current is last, open NAV side.
- Support one key to delete for input field.
- Now you can add feed to Feedbin.(Title and category in subscription dialog not work, and not support unsubscribe)
- Update Korean, Hungarian, Portuguese (Brazil), Romanian.
- Fixed share content issue.

# 2.6 2016-12-18
- Support TeslaUnread. And use these codes to get unread count and sync time for developers:
```
    Intent batteryIntent = context.registerReceiver(null, new IntentFilter("com.seazon.feedme.ACTION_UNREAD_COUNT"));
    int unreadCount = batteryIntent.getIntExtra("UNREAD_COUNT", -1);
    long syncTime = batteryIntent.getLongExtra("SYNC_TIME", -1);
```
- Improve E-Ink experience. Some optimizations are only effective for E-Ink theme.
- Build-in save page function, including images. You can save page via "Share content" and choose "Save html".
- Add "Indent" option in article view dialog.
- Rename widget.
- Remove Readability service.
- Fixed audio tag issue.
- Other bugfixes and improvements.

###### 2.5.6 2016-11-27
- The Readability Parser API will shut down December 10, 2016. And now FeedMe supports Mercury mobilizer. Another mobilizer Google web light seems to have some problems in FeedMe.
- New setting Interface - Navigation Bar, fix the wrong FAB or bottom bar position.
- Update Portuguese (Brazil).
- Fixed show same pictures in article. Only works on newly downloaded articles.
- Fixed save picture failed issue.
- Other bugfixes and improvements.

###### 2.5.5 2016-10-28
- Support Indonesian.
- Update German.
- Align add "justify" option.
- Gif in item list play one time if not move.
- Embedly mobilizer now can shows error information correctly.
- Pocket mobilizer does not work anymore, removed.
- Update okhttp 2.3.0 -> 3.4.1.

###### 2.5.4 2016-9-20
- Fixed split action bar issue.
- Fixed scroll bar issue.
- Fixed side nav header issue.

###### 2.5.3 2016-9-10
- Improve immersive mode, now there are three options.
- Now sync notification also shows new item count.
- Improve checkbox style for Android 4.0.
- Improve switch style for Android 4.0 ~ 4.4.
- Fixed authentication expired issue, now a dialog will show to re-authentication.

###### 2.5.2 2016-8-27
- Improve audio tag and video tag in article page. Now it displays an icon, tap to open audio/video app to play.
- Update Spanish, Russian.
- Some improvements.
- Fixed font load issue.
- Fixed only sync when charging issue.

###### 2.5.1 2016-8-13
- New widget.
- Update Spanish, Russian, German, Polish.
- Some improvements.

# 2.5 2016-7-8
- Now you can customize menus on actionbar and FAB(floating action button), set one FAB and some menus show if space is enough(if no space, show in overflow), set some menus always in overflow, set some menus disable, and re-order them.
adapter for all activities.
  - update split actionbar mode: show actionbar with menus at bottom for phone or show at side for tablet.
  - update handness option: decide FAB, side actionbar and swipe back at which side: left or right.
  - long press actionbar title to enter edit mode.
  - provide back, up and down menu for tablet, you also can use them on phone.
- Improve actionbar and animation
  - transparent actionbar for android 5.0+.
  - scroll up to hide actionbar and scroll down to show.
  - scroll down to the bottom to show actionbar again, if in immersive mode article page, actionbar won't show.

###### 2.4.2 2016-7-6
- Support mute keywords(in feed manager dialog).
- Update Portuguese (Brazil), Romanian.

###### 2.4.1 2016-6-7
- New option to disable pull to refresh in article list page.
- New option to open image in third party image browser.
- New option to save image when long press on image in article page.
- Improve sync issue for Android 6.0 Doze feature.
- Other bugfixes and improvements.
- Add local RSS feature, but not ready related plug-ins.

# 2.4 2016-5-16
- Add new launch mode (Settings - Interface) : Launch screen is article list, right swipe to open nav side, and back button to article list, and back again to exit.
- Improve subscription
    - Now you can manager category in subscription page. Tap category to show category setting dialog.
    - Layout (List, Card, etc.) is now remembered for each feed and category.
    - Set different mobilizer for different feed/category.
    - Set keywords for feed to filter articles. Once the keywords seted for feed, only the articles which title contains the keywords will reserved, other articles will mark as read. You can set more than one keyword for one feed, split them by ";". If you want to add a filter which need both meet two keywords or more, connect them by "+".
- Sync mode:
  - by feed : The sync mode we used before 2.4. Sync articles group by feed. You can disable sync some feeds.
  - by category : Sync articles group by category. You CAN'T sync uncategoried feeds. You can disable sync some categories, but CAN'T disable sync some feeds.
  - by all : Sync articles just order by time. The fastest way to sync. You CAN'T disable sync some feeds or categories. This is the sync mode if you enable "China Mode" before 2.4.
- Support Dutch.
- Improve dialog width for tablet.
- Fixed Feedbin button issue.
- Fixed list jump issue when add article to Pocket in article list page.

# 2.3 2016-4-18
- Support Feedbin.
- Add In-app Billing (Settings - About).
- Fixed margin, line-height, align setting reset issue.

###### 2.2.9 2016-4-11
- New option in Feed Setting: Download web page when reading. (via Readability mobilizer)
- Now starred items won't download web page if this feed not enable download web page when sync.
- New layout：Vision.
- Support video tag in article page.
- Add margin, line-height, align in view menu of article page.
- Update Hungarian, Spanish.
- Improve image browser.
- Update library: android support lib:23.1.1 -> 23.3.0, glide:3.6.1 -> 3.7.0, PhotoView:1.2.2 -> 1.2.5.

###### 2.2.8 2016-4-7
- Update German.
- Fixed a sync issue of InoReader OAuth 2. You need re-login to solve this bug.

###### 2.2.7 2016-3-30
- Support Hungarian, update Spanish, Portuguese (Brazil), French, Russian, Ukrainian, Japanese.
- User authentication via OAuth 2.0 for InoReader.
- Support copy to clipboard menu when long press in article list.
- Fixed a sync issue of The Old Reader.

###### 2.2.6 2016-3-24
- Add open source licenses page in setting.
- Improve Everntoe sharing.
- Improve progress bar style.
- Improve FAB: show in left/right base on One-Hand Operation setting.
- Update Russian, French and Spanish.
- Minimum support from 2.3 to 4.0.
- Custom events.

###### 2.2.5 2016-3-13
- Fix sync issue.

###### 2.2.4 2016-3-11
- Update for InoReader user.
- Get more information <a href="https://plus.google.com/100365587272890955375/posts/MffXHfkUBB8">here</a>

###### 2.2.3 2016-3-10
- Bugfixes and improvements.

###### 2.2.2 2016-3-9
- Update Spanish and Russian.
- Fixed crash issue while mark all read.
- Fixed wrong category counts issue.
- Other bugfixes and improvements.

###### 2.2.1 2016-2-28
- New layout "Summary" which show title and summary.
- Now you can change font in list page via view menu.
- Now sync progress won't show in notification bar, but in nav side. And also will show when auto sync.
- Now changing theme in list page won't open drawer.
- Now changing theme in setting page won't reset to sync tab.
- Now list page uses regular font, not light font, for readability.
- Now alert dialog will show at bottom if enable split action bar (settings - control).
- Other UI improvements.
- No longer support Android 2.2 for network issue.

# 2.2 2016-2-15
- Support auto theme change (settings - ui). If using Light or Paper theme, auto change to Dark theme when before 6 am or after 18 pm.
- Add more actions for double touch in article page.
- Tap action bar title to back to top for list and article page.
- Read and unstarred item title shows a lighter color.
- Improve setting page.
- Improve theme change animation.
- Improve mobilizer tag.
- Fixed some FC issues.
- Improve Overdraw.

###### 2.1.1 2016-2-4
- Fixed sync issue occur in 2.1.0.

# 2.1 2016-1-29 2016-2-4
- Support in app search.
- Optimize manual synchronization.
- Support share to Wiz note.
- Add "keep unread" for swipe fast action.
- Optimize article page tag h1~h6.
- Fixed nav side group expand issue.
- Fixed a FeedMe mobilizer bug.
- Fixed subscription issue.
- Adjust font size of article list summary and article page title.
- Support android 6.0 permission.
- Get more information <a href="https://plus.google.com/100365587272890955375/posts/dVqaNifMSsZ">here</a>

###### 2.0.6 2016-1-17
- Improve FAB show again when scroll to bottom.
- Improve FAB hide/show via volume buttons navigation.
- Fixed some favicons not show issue.
- Fixed can't save image issue.

###### 2.0.5 2015-12-24
- Fixed can't open article and FC(sometimes) issue.

###### 2.0.4 2015-12-23
- Fixed can't save to Instapaper issue
- Fixed conflict of swipe and pull to refresh.
- Improve star FAB in article page

###### 2.0.3 2015-12-18
- Sync menu back.
- Fixed FC issue on tablet.
- Other minor changes and bug fixes.

###### 2.0.2 2015-12-16
- Optimize built-in browser.
- Optimize minimal view for small screen.
- Optimize font initialization.
- Remove depricated Instapaper Mobilizer.

###### 2.0.1 2015-11-25
- Fix FC issue when open app in Android 6.0.

# 2.0 2015-11-24
- Pull to refresh.
- Selectable font.
- Adjustable font size in list.
- Card, list, minimal list view, with summary and thumbnail.
- Auto mark read.
- Material elements: ripple, float action bar.
- One more theme: paper.
- Selectable color.
