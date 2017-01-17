# NetcoDocs

1. Add the netco repo to your your project's build.gradle at the end of repositories

/build.gradle
```groovy
allprojects {
	repositories {
		jcenter()
		maven {
            url "http://artifactory-blr.netcodev.com/artifactory/libs-release"
            credentials {
                username repoUsername
                password repoPassword
            }
        }
	}
}
```

2. List of available libraries

```groovy
compile 'com.netcosports.croplibrary:croplibrary:1.0.0'
```

```groovy
compile 'com.netcosports.datadroid:datadroid:1.0.3'
```

```groovy
compile 'com.netcosports.donwloadtranslations:download-translations-task:1.0.2'
```

```groovy
compile 'com.netcosports.materialshowcase:showcase-view:1.0.1'
```

```groovy
compile 'com.netcosports.opta:models:1.0.6'
```

```groovy
compile 'com.netcosports.opta:rxjava:1.0.6'
```

```groovy
compile 'com.netcosports.opta:rxjava2:1.0.6'
```

```groovy
compile 'com.netcosports.passbook:passbook:1.0.0'
```

```groovy
compile 'com.netcosports.scrollbarpanel:scrollbarpanel:1.0.0'
```

```groovy
compile 'com.netcosports.signing:retrofit:1.0.10'
```
	
```groovy
compile 'com.netcosports.twitterlib:twitter:1.0.1'
```
	
```groovy
compile 'com.netcosports.twitterlib2:twitter:1.0.1'
```
	
```groovy
compile 'com.netcosports.utils:asyncimageview:1.0.2'
```
	
```groovy
compile 'com.netcosports.utils:netcoutils:1.0.2'
```
		
```groovy
compile 'com.netcosports.utils:slidingmenu:1.0.0'
```
		
```groovy
compile 'com.netcosports.viewpagerindicators:indicators:1.0.6'
```
