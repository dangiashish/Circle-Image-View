# Circle-Image-View
Custom Circle Image VIew

[![](https://jitpack.io/v/DangiAshish/Circle-Image-View.svg)](https://jitpack.io/#DangiAshish/Circle-Image-View)

#### Gradle
 ```gradle
 allprojects {
		repositories {
			maven { url 'https://jitpack.io' }
		}
	}
 ```
 
 ### Add dependency
 
 ```Dependency
 dependencies {
	        implementation 'com.github.dangiashish:Circle-Image-View:1.0.2'
	}
 ```

### XML
```groovy
<com.codebyashish.CircleImageView
        android:id="@+id/ivUserPic"
        android:layout_width="70dp"
        android:layout_height="70dp"
        android:src="@drawable/ic_user2"
        app:civ_border_color="@color/gray"
        app:civ_border_width="2dp"

        android:layout_gravity="center_vertical"
        android:layout_margin="10dp"/>
```
