#地址：http://anxpp.com/ 

```xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    <com.anxpp.underlinetextview.UnderlineTextView
        android:text="@string/title"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        android:padding="3dp"
        android:textSize="20sp"
        android:textColor="@color/colorAccent"
        android:background="#dad7d7"
        app:underline_color="@color/colorPrimary"
        app:underline_height="3dp"/>
</RelativeLayout>
```
