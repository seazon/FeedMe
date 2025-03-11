From version 2.4, FeedMe supports filter new articles when syncing, mark the articles which you don't want to read as read, to save your time. You can set different filter for each feed.

You can find filter in `feed setting` dialog. There is a switch on left for filter with different way. The edit text below is for writing keywords.

<img src="https://github.com/seazon/FeedMe/blob/master/doc/en/imgs/filter_1.png" width="25%" height="25%" />

## Filter Type
- `Reserved`：Only reserved the articles which contain keywords, others mark read.
- `Mute`：Mark the articles which contains keywords as read.

<img src="https://github.com/seazon/FeedMe/blob/master/doc/en/imgs/filter_2.png" width="25%" height="25%" /> <img src="https://github.com/seazon/FeedMe/blob/master/doc/en/imgs/filter_3.png" width="25%" height="25%" />

If you just want to keep articles which contains some keywords, use `Reserved`. If you don't want to see some keywords, use `Mute`.

## Edit text
- If your keywords is combind wity 2 words, use `+`
- If you have more than 1 keyword, use `;`

## Samples
- if you want to `Reserved` the articles which contains `android`, set switch as `Reserved`, and input `android`
- if you want to `Reserved` the articles which contains both `android` and `google`, set switch as `Reserved`, and input `android+google`
- if you want to `Reserved` the articles which contains both `android` and `google`, also `Reserved` the articles which contains `chrome`, set switch as `Reserved`, and input `android+google;chrome`
- if you want to `Mute` the articles which contains `android`, set switch as `Mute`, and input `android`
- if you want to `Mute` the articles which contains both `android` and `google`, set switch as `Mute`, and input `android+google`
- if you want to `Mute` the articles which contains both `android` and `google`, also `Mute` the articles which contains `chrome`, set switch as `Mute`, and input `android+google;chrome`
