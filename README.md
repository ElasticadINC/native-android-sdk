
NativeAd Android SDK
===========
The  NativeAd Android SDK facilitates inserting native mobile ads into a ListView or other content stream in your Android application. You can choose one of our pre-built sample formats, reuse your existing content layout, or create a new custom format.

Dependency
===========
**Google Play Service project**

NativeAd Android SDK uses the new Google Advertising ID  to identify application users and is not using the legacy  android ID for this scope, to be compliant with the new [Google Play policy](https://support.google.com/googleplay/android-developer/answer/6048248). In order to do this, you will have to add [Google Play Service project](http://developer.android.com/google/play-services/setup.html) as a dependency to NativeAd SDK.

**Android Support Libraries**

EANativeAd SDK uses android support libraries for caching the last loaded images from ads. You can find more information about this library [here](https://developer.android.com/tools/support-library/setup.html)

Quickstart
===========
See our [Quickstart Guide](https://native.atlassian.net/wiki/display/NMS/Integrate+with+Android) to get started.

Change Log
===========
**Version 4.0.9** - *Apr 11, 2016*

New Features 
* New MediaView Object that supports
	* Inline video teaser
	* Multiple images showed in same teaser
* New Format - see eanative_ad_view_sample_4


**Version 3.0.5** - *Jan 18, 2016*

New Features 
* VAST Teaser
* Custom query Params 

**Version 1.2** - *Mar 4, 2015*
	* Added AD_LOAD_ERROR event
	
**Version 1.1** - *Feb 24, 2015*
	* Support for Android Studio

**Version 1.0** - *July 23, 2014*
* First public release!


