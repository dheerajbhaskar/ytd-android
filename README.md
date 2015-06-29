# ytd-android

The code is a reference implementation for an Android OS application that captures video, uploads it to YouTube, and submits the video to a [YouTube Direct Lite](http://code.google.com/p/youtube-direct-lite/) instance. This application utilizes [YouTube Data API v3](https://developers.google.com/youtube/v3/) , [YouTube Android Player API](https://developers.google.com/youtube/android/player/), [YouTube Resumable Uploads](https://developers.google.com/youtube/v3/guides/using_resumable_upload_protocol?hl=en), [Google Play Services](https://developer.android.com/google/play-services/index.html) and [Plus API](https://developers.google.com/+/mobile/android/Google).

<font color="red">To use this application:</font>

1) Register [here](https://developers.google.com/youtube/android/player/register) first and enable Youtube Data API v3 and Google+ API in your [API Console](https://code.google.com/apis/console).

2) Include [Google Play Services library](http://developer.android.com/google/play-services/setup.html) into your project to build this application.

3) This is Maven project, you can use [m2eclipse plugin](http://eclipse.org/m2e/download/) to download dependent libraries and

4) [maven-android-plugin](https://code.google.com/p/maven-android-plugin/) to build for Android device.

5) Plug in your Playlist Id into [Contants.java](https://code.google.com/p/ytd-android/source/browse/trunk/src/com/google/ytdl/Constants.java) and Android API Key into [Auth.java](https://code.google.com/p/ytd-android/source/browse/trunk/src/com/google/ytdl/Auth.java)

<td>![](http://ytd-android.googlecode.com/files/framed_ytdl-screenshot.png)</td>



<td>This project is a work in progress.</td>
