# RatingView
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-RatingView-green.svg?style=true)](https://android-arsenal.com/details/1/3770)

Simple android widget that can replace standard inconvenient RatingBar in your app. Adds ability to set step_size=0.1.

##[Screenshot]
<img width="200" src="https://drive.google.com/uc?id=0B7ZVk3cvDAFAZTUwM3JHdVFvdG8">
##Description
The default Android `RatingBar` widget hardly can satisfy developers' needs. It's a pain to customize it at all. This simple view can take a huge advantage of setting and scaling drawables for rating view easily.
##Installation
To use the library, first include it your project using Gradle
```gradle
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
dependencies {
	compile 'com.github.anchik12345:RatingView:97da92a481'
}
```	
##Example
Declare `RatingView` in your XML with `app` attributes:
```xml
<com.github.ornolfr.ratingview.RatingView
	android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:drawable_empty="@drawable/ic_star_empty"
    app:drawable_filled="@drawable/ic_star_filled"
    app:drawable_half="@drawable/ic_star_half"
    app:drawable_margin="4dp"
    app:drawable_size="24dp"
    app:is_indicator="false"
    app:max_count="5"
    app:rating="3.5" />
```
And use it through `RatingView` instance in your code. Goog luck!
