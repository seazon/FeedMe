# 4.2.0
###### 2024-3-4
- [new] Support local RSS.
- [new] Add Miniflux service.
- [new] UI redesign.
  - Login screen.
  - Subscription list & detail screen.
  - New OPML feed selection dialog.
  - Move `Settings` - `Sync` - `Advanced` to subscription list screen.
- [new] Feedly support edit subscription.
- [optimize] FeedMe no longer responds to http/https URL intent from external app. https://github.com/seazon/FeedMe/issues/678
- [optimize] Add option(`Settings` - `Interface` - `Full Screen Playback`) to disable auto landscape when playing video in full screen. https://github.com/seazon/FeedMe/issues/661
- [optimize] Support Feedbin thumbnails. https://github.com/seazon/FeedMe/issues/646
- [optimize] Adjust video height. https://github.com/seazon/FeedMe/issues/675
- [optimize] Always show sync icon on NAV side. https://github.com/seazon/FeedMe/issues/682
- [optimize] Adjust sync loading indicator offset. https://github.com/seazon/FeedMe/issues/681
- [fix] Fix OPML import not work on Android 14.
- [fix] Other minor updates.

### 4.1.8
###### 2024-1-18
- [fix] Fix scrolling freezes issue when navigating previous or next articles. https://github.com/seazon/FeedMe/issues/671

### 4.1.7
###### 2024-1-5
- [fix] Fix crash issue.

### 4.1.6
###### 2023-12-31
- [fix] Fix the problem of exiting abnormally after video full screen. https://github.com/seazon/FeedMe/issues/665

### 4.1.5
###### 2023-12-07
- [optimize] Improve style for HTML code tag.
- [optimize] New option in `setting` - `control` to disable open image in article page.
- [fix] Fix wrong parsing in code tag. https://github.com/seazon/FeedMe/issues/659
- [fix] Fix some crash issues.

### 4.1.4
###### 2023-11-27
- [fix] Fix crash while play audio on Android 14.
- [fix] Fix the `Split Action Bar` description error. https://github.com/seazon/FeedMe/issues/660

### 4.1.3
###### 2023-11-12
- [fix] Fix LED color config issue. https://github.com/seazon/FeedMe/issues/654

### 4.1.2
###### 2023-11-9
- [optimize] Improve NAV side header layout.
- [optimize] Improve alert popup.
- [fix] Fix pre tag format issue. https://github.com/seazon/FeedMe/issues/652

### 4.1.1
###### 2023-10-23
- [fix] Upgrade lib version.

# 4.1
###### 2023-10-21
- [new] FeedMe Mobilizer Selector. https://github.com/seazon/FeedMe/issues/622
- [new] New widget: player widget.
- [optimize] `Settings` - `Interface` - `Layout`, more options for layout.
- [optimize] Update switch style.
- [fix] Fix image parser issue for FeedMe Mobilizer. https://github.com/seazon/FeedMe/issues/364

### 4.0.4
###### 2023-10-8
- [optimize] Include highlighter data in backup. https://github.com/seazon/FeedMe/issues/615
- [fix] Fix Feedbin mobilizer issue. https://github.com/seazon/FeedMe/issues/602 https://github.com/seazon/FeedMe/issues/577

### 4.0.3
###### 2023-10-6
- [fix] Fix not possible to set auto sync interval of 4 hours. https://github.com/seazon/FeedMe/issues/630
- [fix] Fix dark mode not work in built-in web browser.

### 4.0.2
###### 2023-9-15
- [optimize] Support set article list margin.
- [fix] Fix show side nav not working when launch. https://github.com/seazon/FeedMe/issues/612
- [fix] Fix sync on app start is not working issue. https://github.com/seazon/FeedMe/issues/607
- [fix] Fix back action wrong logic.

### 4.0.1
###### 2023-9-2
- [optimize] Adjust the minimum value of article page margin.
- [fix] Fix the problem that the page margin of the article is too large.
- [fix] Fix the problem of automatically scrolling to the last reading position when opening the app. https://github.com/seazon/FeedMe/issues/591
- [others] Remove AD.

### 4.0.0
###### 2023-8-30
- [fix] Fix failed to import/export OPML issue.

### 4.0.0-Canary-11
###### 2023-8-20
- [DE-BUFF] Show AD in article list.
- [optimize] Tips for add to ignore battery optimizations whitelist. https://github.com/seazon/FeedMe/issues/91#issuecomment-1683809364
- [optimize] Sync interval add new option: 10 minutes.
- [optimize] Disable `Compact Layout` will always show single screen. https://github.com/seazon/FeedMe/issues/556#issuecomment-1660290318
- [fix] Fix images are showed in music format. https://github.com/seazon/FeedMe/issues/364
- [fix] Fix bluetooth controls not work issue. https://github.com/seazon/FeedMe/issues/581
- [fix] Fix can't auto mark read when reach the bottom. https://github.com/seazon/FeedMe/issues/574

### 4.0.0-Canary-10
###### 2023-8-2
- [fix] Fix mobilizer not work issue. https://github.com/seazon/FeedMe/issues/567

### 4.0.0-Canary-9
###### 2023-8-1
- [new] Add compact layout option. https://github.com/seazon/FeedMe/issues/556
- [fix] Fix crash issue when update sync interval. If you upgrade from Canary 8, need update `Settings` - `Cache` - `Reading List` to avoid crash again. https://github.com/seazon/FeedMe/issues/561 
- [fix] Fix images are showed in music format. https://github.com/seazon/FeedMe/issues/364
- [fix] Fix menu bar disappears after switching from "Starred items" to "All items". https://github.com/seazon/FeedMe/issues/560
- [fix] Fix sidebar not clickable after exiting from fullscreen video. https://github.com/seazon/FeedMe/issues/554

### 4.0.0-Canary-8
###### 2023-7-29
- [optimize] Add option for flip percent.
- [optimize] New color picker for accent color and highlighter color.
- [optimize] Alert dialog button list vertically.
- [optimize] Show url in url dialog. https://github.com/seazon/FeedMe/issues/517#issuecomment-1629953259
- [optimize] Nav can close by swipe now. https://github.com/seazon/FeedMe/issues/546
- [optimize] Optimize the color of selected item. https://github.com/seazon/FeedMe/issues/538
- [fix] Fix can't mark read for double panel case. https://github.com/seazon/FeedMe/issues/543
- [fix] Always show tool bars when immersive off.
- [fix] Add bottom space for navigation bar. https://github.com/seazon/FeedMe/issues/553

### 4.0.0-Canary-7
###### 2023-7-14
- [optimize] Remember article position. https://github.com/seazon/FeedMe/issues/526
- [optimize] Better support for navigation bar if it shows at left or right of screen.
- [fix] Fix crash issue while share in built-in browser. https://github.com/seazon/FeedMe/issues/522#issuecomment-1605891128
- [fix] Fix can't load second page for article list. https://github.com/seazon/FeedMe/issues/542

### 4.0.0-Canary-6
###### 2023-6-22
- [fix] Fix large blank on article list. https://github.com/seazon/FeedMe/issues/532

### 4.0.0-Canary-5
###### 2023-6-21
- [fix] Fix action bar menus not show correctly. https://github.com/seazon/FeedMe/issues/517#issuecomment-1594359875
- [fix] Fix article list scroll automatically when back from other screen. https://github.com/seazon/FeedMe/issues/528

### 4.0.0-Canary-4
###### 2023-6-17
- [new] Click the feed title in article page to goto this feed's article list page. https://github.com/seazon/FeedMe/issues/523
- [optimize] Update immersive mode. https://github.com/seazon/FeedMe/issues/517#issuecomment-1590289087
- [fix] Fix Tiny Tiny RSS can't fetch unread items issue. https://github.com/seazon/FeedMe/issues/525
- [fix] Video stop play after rotate screen. https://github.com/seazon/FeedMe/issues/517#issuecomment-1586380529
- [fix] Fix crash issue while share to Wechat. https://github.com/seazon/FeedMe/issues/522#issuecomment-1593792701

### 4.0.0-Canary-3
###### 2023-6-15
- [fix] Fix the problem that the article page menu is not updated. https://github.com/seazon/FeedMe/issues/517#issuecomment-1589336638
- [fix] Fix pull-to-refresh not working. https://github.com/seazon/FeedMe/issues/517#issuecomment-1589351824

### 4.0.0-Canary-2
###### 2023-6-13
- [fix] Accent background color issue on article list. https://github.com/seazon/FeedMe/issues/517#issuecomment-1586292674
- [fix] The name and the actual function do not match for swipe left and right feature. https://github.com/seazon/FeedMe/issues/517#issuecomment-1587651850

# 4.0.0-Canary-1
###### 2023-6-11
#### New UI based on Material You
- Flattened cards, rounded corners *
- Accent color uses desaturated color in dark mode
- Launch icon support Material You (Android 13+)
#### Large screen adaptation
- Display different layouts according to screen size
- Keyboard shortcut support *
#### Audio
- Support direct streaming, no download required
- Audio support for skipping silence
- sleep time supports the end of a single episode
- Support playing searched, unsubscribed episodes
- Remove the star addition function in the player interface
- Podcast download configurable
#### Video
- Video supports full-screen playback
#### Subscribe
- When entering some website addresses, it will be automatically converted to rss addresses *
#### Other
- Mark read optimization
  - When long press to mark all read, more options will pop up (mark one day ago as read, mark one week ago as read)
  - Long press the article besides mark above as read, add mark below as read
- Remove the feature and setting item that the picture on the article page occupies the full width, and now it is always aligned with the text
- Optimize favicon display *
- Article Paragraph Table of Contents *
- New in-app payment item: Durian
- When the built-in browser opens an external link, there will be a prompt, and it can remember your choice. You can also reset it in Settings-Cache-Clear Default Action.

`*` indicates that the function is available, but it will continue to be improved in future versions
