## Permissions

##### `android.permission.READ_PHONE_STATE`
Since version 3.0, FeedMe added TTS and podcast feature. For a better experience, When there is a call, it will automatically suspend audio playback. 

So FeedMe need this permission to achieve this suspending function.

## External server
- FeedMe has no server to save your data.
- FeedMe uses RSS server APIs to get feeds data for you.

## Q&A
##### Q:Does FeedMe only connect to my RSS provider like Feedbin and only connects to external addresses that are listed in my feeds?
A: Yes.

##### Q:Does FeedMe collect any data and phone home to you or a third party? If so, what? Is the list of my feeds transmitted? Is my IMEI transmitted? Is any information about what I have in my storage transmitted?
- FeedMe won't collect your any data and save them.
- Your feeds won't be transmitted.
- FeedMe won't use your other information in your storage.

##### Q:Is any third party library used that tracks?
A: I have listed the third party libraries ( https://github.com/seazon/FeedMe/blob/master/doc/en/licenses.md ). You can check their documents and source codes.