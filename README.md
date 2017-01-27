# NetcoDocs

1. Add the netco repo to your your project's build.gradle at the end of repositories

/build.gradle
```groovy
allprojects {
	repositories {
		jcenter()
		maven {
            url "https://artifactory-blr.netcodev.com/artifactory/libs-release"
            credentials {
                username repoUsername
                password repoPassword
            }
        }
	}
}
```

2. List of available libraries

[GradleDownloadTranslationPlugin](https://github.com/netcosports/GradleDownloadTranslationPlugin)

To download translations from Netco parse

```groovy
compile 'com.netcosports.donwloadtranslations:download-translations-task:1.0.2'
```

[DataDroid](https://github.com/netcosports/DataDroid) 

Contains DataDroid and DataDroidCompat modules combined into one
```groovy
compile 'com.netcosports.datadroid:datadroid:1.0.3'
```

[NetcoPushGCM](https://github.com/netcosports/NetcoPushGCM) 

Contains Signing Library for DataDroid and play services gcm 
```groovy
compile 'com.netcosports.push:pushgcm:1.0.2'
```

[Players](https://github.com/netcosports/android-player-view)

exoplayer branch

```groovy
 com.netcosports.player:exoplayer:1.0.0
 ```

[NetcoOptaModels](https://github.com/netcosports/NetcoOptaModels_Android)

Contains opta models with simplexml parsers, and retrofit service for rxjava and rxjava2


```groovy
compile 'com.netcosports.opta:models:1.0.6'
```

```groovy
compile 'com.netcosports.opta:rxjava:1.0.6'
```

```groovy
compile 'com.netcosports.opta:rxjava2:1.0.6'
```
[TwitterNetcoLibV2](https://github.com/netcosports/TwitterNetcoLibV2)

Fabric based twitter lib implementation

	
```groovy
compile 'com.netcosports.twitterlib:twitter:1.0.1'
```
	
```groovy
compile 'com.netcosports.twitterlib:twitter2:1.0.2'
```

[TwitterNetcoLib](https://github.com/netcosports/TwitterNetcoLib)

Old twitter lib

```groovy
	com.netcosports.twitterlib:ancient-twitter:1.0.0
```

[ViewPagerIndicators](https://github.com/netcosports/ViewPagerIndicator)

Netco view pager indicators. Also contains inside [PagerSlidingTabStrip](https://github.com/netcosports/PagerSlidingTabStrip)

		
```groovy
compile 'com.netcosports.viewpagerindicators:indicators:1.0.6'
```

Signing Libraries

[Signing Library for DataDroid](https://github.com/netcosports/AndroidSigningLib)

```groovy
compile 'com.netcosports.signing:datadroid:1.0.0'
```
[Signing Library for Retrofit](https://github.com/netcosports/AndroidSigningClient_Retrofit)
```groovy
compile 'com.netcosports.signing:retrofit:1.0.13'
```

Utils

[RtlWidgets](https://github.com/netcosports/RtlWidgets_Android)

```groovy
compile 'com.netcosports.utils:rtlwidgets:1.0.0'
```

[AsyncImageView](https://github.com/netcosports/AndroidAsyncImageView)
```groovy
compile 'com.netcosports.utils:asyncimageview:1.0.2'
```

[NetcoUtils](https://github.com/netcosports/NetcoUtilsAndroid)
```groovy
compile 'com.netcosports.utils:netcoutils:1.0.2'
```

[SlidingMenu](https://github.com/netcosports/SlidingMenuAndroid)
```groovy
compile 'com.netcosports.utils:slidingmenu:1.0.0'
```

[CropLibary](https://github.com/netcosports/CropLibraryCompat)
```groovy
compile 'com.netcosports.croplibrary:croplibrary:1.0.0'
```
Player

[MediaPlayerControl](https://github.com/netcosports/MediaPlayerControlAndroid)

```groovy
 com.netcosports.player:mediaplayercontrol:1.0.0
```

Calendars

[MaterialCalendar](https://github.com/netcosports/material-calendarview)

```groovy
 com.netcosports.calendars:material-calendarview:1.0.0
```

old
[CalendarV2Lib](https://github.com/netcosports/CalendarV2Lib_Android)

```groovy
 com.netcosports.calendars:squareup:1.0.0
```	

Others:

[MaterialShowCaseView](https://github.com/netcosports/MaterialShowcaseView)

```groovy
compile 'com.netcosports.materialshowcase:showcase-view:1.0.1'
```

[PassbookAnroid](https://github.com/netcosports/PassbookAndroid)

```groovy
compile 'com.netcosports.passbook:passbook:1.0.0'
```

[ScrollBarPanelLib](https://github.com/denisshikunets/Android-ScrollBarPanel)

```groovy
compile 'com.netcosports.scrollbarpanel:scrollbarpanel:1.0.0'
```
