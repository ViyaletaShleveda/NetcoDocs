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

[DataDroid](https://github.com/netcosports/DataDroid) 

Contains DataDroid and DataDroidCompat modules combined into one
```groovy
compile 'com.netcosports.datadroid:datadroid:1.0.3'
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
compile 'com.netcosports.twitterlib2:twitter:1.0.1'
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
compile 'com.netcosports.signing:retrofit:1.0.10'
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

Others:



```groovy
compile 'com.netcosports.donwloadtranslations:download-translations-task:1.0.2'
```

```groovy
compile 'com.netcosports.materialshowcase:showcase-view:1.0.1'
```

```groovy
compile 'com.netcosports.passbook:passbook:1.0.0'
```

```groovy
compile 'com.netcosports.scrollbarpanel:scrollbarpanel:1.0.0'
```
