# DrawableText
A Textview that allows to set drawable size.

![](https://github.com/developerbenwu/DrawableText/blob/master/screens/device-2015-10-17-125656.png)

# Basic usage
Add the view to your xml layout
```
 <com.ben.view.DrawableText
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:drawableLeft="@drawable/ic_launcher"
    android:text="DrawableText">
```
Specify width and height for the drawable:
```
 <com.ben.view.DrawableText
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:drawableLeft="@drawable/ic_launcher"
    app:left_height="24dp"
    app:left_width="24dp"
    android:text=DrawableText">
```
 
