### 4.4.2
###### 2025-5-6
- [fix] Fix TTRSS synchronization failure and crash issues. https://github.com/seazon/FeedMe/issues/20

### 4.4.1
###### 2025-4-30
- [fix] Fix a crash issue while login.

# 4.4.0
###### 2025-4-30
- [new] Article list title translation. https://github.com/seazon/FeedMe/issues/9
- [optimize] Update Spanish/Russian. https://github.com/seazon/FeedMe/issues/2
- [fix] Fix issue of time-consuming loading of articles. https://github.com/seazon/FeedMe/issues/14
- [fix] Webp image not show issue. https://github.com/seazon/FeedMe/issues/4

### 4.3.10
###### 2025-3-29
- [optimize] Update Spanish.
- [fix] Fix load web failed for WeChat Official Account link. https://github.com/seazon/FeedMe/issues/8
- [fix] Fix some tiny issues.

### 4.3.9
###### 2025-3-8
- [optimize] Update Chinese and German. https://github.com/seazon/FeedMe/issues/639#issuecomment-2609741358
- [fix] Fix sync never finishing issue. https://github.com/seazon/FeedMe/issues/778
- [fix] Fix crash issue. https://github.com/seazon/FeedMe/issues/809

### 4.3.8
###### 2025-2-22
- [new] New menu `Play list (title only)` on article list page.
- [optimize] New option to hide favicon. https://github.com/seazon/FeedMe/issues/444
- [optimize] Update article list max lines to 3 for widget.
- [fix] Fix widget image not display issue. https://github.com/seazon/FeedMe/issues/600
- [fix] Fix crash issues.

### 4.3.7
###### 2025-2-4
- [optimize] Image download and display logic update. https://github.com/seazon/FeedMe/issues/796
- [optimize] Display favicon in article list. https://github.com/seazon/FeedMe/issues/444
- [fix] Fix Thumbnails don't show in `Modern` and `Twitter` view. https://github.com/seazon/FeedMe/issues/795 https://github.com/seazon/FeedMe/issues/784
- [fix] Open image when tapping on image with link. https://github.com/seazon/FeedMe/issues/782 
- [fix] Fix missing widget rounded corners on some Android 15 devices.

### 4.3.6
###### 2025-1-8
- [optimize] New font: Atkinson Hyperlegible. https://github.com/seazon/FeedMe/issues/779
- [optimize] Play audio in FeedMe while tap audio icon in article page. https://github.com/seazon/FeedMe/issues/653
- [fix] Fix JSON Parse Error when syncing with Commafeed/Fever API. https://github.com/seazon/FeedMe/issues/695
- [fix] Fix crash issue.

### 4.3.5
###### 2024-12-2
- [fix] Fix `Settings`, `Explore` and `Subscriptions` isn't working on large screen. https://github.com/seazon/FeedMe/issues/772

### 4.3.4
###### 2024-12-1
- [fix] Fix crash issue on large screen. https://github.com/seazon/FeedMe/issues/772

### 4.3.3
###### 2024-11-30
- [optimize] Support Http proxy. https://github.com/seazon/FeedMe/issues/749#issuecomment-2439908378
- [optimize] Improve feed title color in dark theme. https://github.com/seazon/FeedMe/issues/767
- [optimize] Support customize Listen Note API token(for podcast search in `Explore` page) in `Settings` -> `Integrations`.
- [fix] Fix incorrect reading time issue. https://github.com/seazon/FeedMe/issues/761 / https://github.com/seazon/FeedMe/issues/764
- [fix] Fix Nav side count not update issue. https://github.com/seazon/FeedMe/issues/768

### 4.3.2
###### 2024-11-13
- [optimize] New option in feed settings to show/hide enclosure images of article. https://github.com/seazon/FeedMe/issues/170
- [optimize] Support for HTTP basic authentication. https://github.com/seazon/FeedMe/issues/345
- [fix] Fix crash issues.

### 4.3.1
###### 2024-10-20
- [optimize] Article list widget count configurable. https://github.com/seazon/FeedMe/issues/600
- [optimize] Display small image placeholder in article page. https://github.com/seazon/FeedMe/issues/740
- [fix] Fix article deeplink issue. https://github.com/seazon/FeedMe/issues/755 
- [fix] Fix podcast time parse error in player show note.
- [fix] Fix crash issues.

# 4.3.0
###### 2024-9-27
- [new] New widget: Article list.
- [optimize] Improve NAV panel on article detail page. https://github.com/seazon/FeedMe/issues/642
- [fix] Fix images are downloaded on mobile data despite setting Wi-Fi only option. https://github.com/seazon/FeedMe/issues/740
- [fix] Fix mark all read but still can see the items. https://github.com/seazon/FeedMe/issues/743
- [fix] Fix some integration app always show in menu. https://github.com/seazon/FeedMe/issues/729
- [fix] Fix E-Ink theme logic issue.

### 4.2.10
###### 2024-8-24
- [optimize] Add transparent touch area on article detail page to scroll up and down, only work for E-ink theme. https://github.com/seazon/FeedMe/issues/642
- [optimize] Share Template support author and date. https://github.com/seazon/FeedMe/issues/732
- [fix] Thumbnails switch should not display for `Modern` view. https://github.com/seazon/FeedMe/issues/728
- [fix] Optimize the lag when switching fragment on NAV side bar.
- [fix] Fix crash issues.

### 4.2.9
###### 2024-7-19
- [optimize] Optimize image loading logic to solve some issues:
  - Note: This version will affect the display of downloaded images. Please clear cache and resynchronize after updating the version for a better experience.
  - Speed up image show in article page. https://github.com/seazon/FeedMe/issues/721 
  - Fix image not show issue. https://github.com/seazon/FeedMe/issues/686 
  - Fix show first image when click any image issue. https://github.com/seazon/FeedMe/issues/379
- [fix] Fix RSS URL parse issue.

### 4.2.8
###### 2024-7-12
- [fix] Fixed selected category is expanded on Nav side.

### 4.2.7
###### 2024-7-11
- [optimize] Add `Anti-Accidental Touch` option in `Lab`. https://github.com/seazon/FeedMe/issues/720
- [fix] Fix not moves to the next feed/category while mark all read. https://github.com/seazon/FeedMe/issues/713
- [fix] Fix favicons not display issue. https://github.com/seazon/FeedMe/issues/714
- [fix] Remove Google Web Light mobilizer. https://github.com/seazon/FeedMe/issues/719
- [fix] Fix some tiny issues.

### 4.2.6
###### 2024-7-7
- [fix] Reduces the probability of crash. https://github.com/seazon/FeedMe/issues/718

### 4.2.5
###### 2024-7-4
- [fix] New option(Settings -> Lab -> disable Enable Browser JavaScript) to disable JavaScript to solve webview blank page issue temporary. https://github.com/seazon/FeedMe/issues/700
- [fix] Fix crash issue.

### 4.2.4
###### 2024-6-22
- [optimize] Show feed url in feed setting page.
- [fix] Fix crash while tap on NAV side.
- [fix] Fix icon non-clickable issue. https://github.com/seazon/FeedMe/issues/693#issuecomment-2145085680
- [others] Upgrade 3rd party libraries.

### 4.2.3
###### 2024-6-3
- [optimize] Support search by author and text. https://github.com/seazon/FeedMe/issues/703
- [optimize] Feed filter also works for article text. https://github.com/seazon/FeedMe/issues/672
- [optimize] Upgrade German. @IngoBN
- [fix] Fix incorrect expansion behavior when clicking on the NAV bar icon. https://github.com/seazon/FeedMe/issues/693
- [fix] Fix auto mark read not work for button navigation.
- [fix] Fix video can't play issue. https://github.com/seazon/FeedMe/issues/708
- [fix] Fix crash issue.

### 4.2.2
###### 2024-5-11
- [fix] Fix the issue of playing the article list content when using talkback tools on the article page.
- [fix] Fix image block not work issue. https://github.com/seazon/FeedMe/issues/701
- [fix] Fix WebView not support adjust layout in full screen mode when soft keyboard is visible .
- [fix] fix duplicate items in login screen. https://github.com/seazon/FeedMe/issues/688#issuecomment-2020040906

### 4.2.1
###### 2024-3-9
- [new] Add new option to disable auto marking as read. https://github.com/seazon/FeedMe/issues/531
- [optimize] Update Italian.
- [fix] Fix subscription issue. https://github.com/seazon/FeedMe/issues/683
- [fix] Fix crash and performance issue on subscription detail screen.

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
