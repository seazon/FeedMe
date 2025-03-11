# Synchronously
FeedMe provides multiple synchronization methods:
1. Complete automatic synchronization
2. Fast automatic synchronization
3. Complete manual synchronization
4. Quick manual synchronization

## Complete automatic synchronization
Automatically synchronize after a certain interval. The interval time can be set in `Settings`-`Synchronization`-`Automatic synchronization`-`Sync interval`. The Android system has a sleep mechanism, so it does not synchronize automatically as soon as the interval expires. There is usually a delay.

A full manual sync will do:
1. Synchronize read, star, and tags to the server
2. Fetch unread items
3. Grab the starred items
4. Download images and full text
5. Download podcasts

## Fast automatic synchronization
Automatically sync when opening the app. In `Settings`-`Sync`-`Auto-sync`-enable `Auto-sync when opening apps`

Quick Auto Sync will do:
1. Synchronize read, star, and tags to the server
2. Fetch unread items

## Complete manual synchronization
The button has two display locations: the `Sync` button in the upper right corner of the sidebar or the `Sync` menu in the list page menu. The latter needs to be turned off in `Settings`-`Interface`-`Side Nav` to be displayed.

A full manual sync will do:
1. Synchronize read, star, and tags to the server
2. Fetch unread items
3. Grab the starred items
4. Download images and full text
5. Download podcasts

### Advanced synchronization dialog box
In `Settings`-`Sync`-enable `Show synchronization method`, after clicking the synchronization button, the synchronization option box will be displayed, and you can select the items that need to be synchronized this time.

## Quick manual synchronization
Pull down on the list page to trigger synchronization. This needs to be enabled in Settings-Control-Pull-to-refresh.

Quick sync will only do:
1. Synchronize read, star, and tags to the server
2. Fetch unread items

Compared with the previous three synchronization ways, which will synchronize all feeds, the `quick manual synchronization` will synchronize specific content based on the current display list. for example,
- When the list is `all items`, all feeds will be synchronized.
- When the list is `starred items`, only starred articles will be synchronized.
- When the list is a `category`, articles from all feeds under this category will be synchronized.
- When the list is a single `feed`, only the articles from this feed will be synchronized.

# Unread count of synchronization
The number of unread items to synchronize is set in `Settings`-`Cache`-`Reading List`. If 500 are set, and the number of unread items on the server side is greater than 500, the latest 500 will be downloaded for each synchronization. If it is less than 500, download all of them.

When there are already 500 unread items, synchronize again and there are 10 new unread items on the server. Then the 10 oldest unread items in FeedMe will be marked as read locally in FeedMe, but will not be synchronized to the server. .

# Sync mode
Provide multiple synchronization modes to meet different needs.

## All
Synchronize only based on the publish time of the article.

Example:
- Download latest 250 unread
- Download 100
- Download 100
- Download 50

This method is the fastest way to download, but you cannot exclude certain `feeds` or `categories`.

Note: If the `China Mode` is enabled, the `All` mode is mandatory.

## Categories
Sync by category

Example:
- 90 unread items wait to download, these 90 unread items belong to 3 `categories`
- sort these `categories`, fewer unread count has higher priority to sync.
- category A has 10 unread items, category B has 30 unread, category C has 50 unread
- Download category A 10
- Download category B 20
- Download category C 20
- Download category B 10
- Download category C 20
- Download category C 10

Can exclude certain categories, but can't exclude feeds.

Note that synchronization by `category` cannot be synchronized to articles from uncategorized feeds.

## Feeds
Sync by feed

Example:
- 90 unread items wait to download, these 90 unread items belong to 3 `feeds`
- sort these `feeds`, fewer unread count has higher priority to sync.
- feeds A has 10 unread, feed B has 30 unread, and feed C has 50 unread
- Download feed A 10
- Download feed B 20
- Download feed C 20
- Download feed B 10
- Download feed C 20
- Download feed C 10

Can exclude certain feeds, but can't exclude categories.