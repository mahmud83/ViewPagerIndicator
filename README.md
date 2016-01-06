Android ViewPagerIndicator
==========================

Since the original library has not changed at all by 3 years, i decided to fix some depreciations. (And meanwhile i converted it into AndroidStudio Project of course)

To include your project, get aar file from [here][1] and put it into 'libs' folder, then have project's gradle file following lines:

```groovy
android {
	...

	repositories {
    	    flatDir {
        	    dirs 'libs'
        	}
    	}
	
	...
}

dependencies {
	compile(name: 'viewpagerindicator', ext: 'aar')	
}
```

[1]: https://github.com/yayaa/ViewPagerIndicator/aar