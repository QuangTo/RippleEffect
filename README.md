# RippleEffect
RippleEffect Example Recyclerview, View, Button ..etc.

Custom_bg : 

<?xml version="1.0" encoding="utf-8"?>
<selector xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:state_pressed="true">
        <shape>
            <solid android:color="@android:color/holo_blue_light"></solid>
        </shape>
    </item>
    <item>
        <shape>
            <solid android:color="@android:color/white"></solid>
        </shape>
    </item>
</selector>

Custom_bg-v21: 

<?xml version="1.0" encoding="utf-8"?>
<ripple
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:color="@android:color/holo_blue_light">
    <item
        android:id="@android:id/mask"
        android:drawable="@android:color/white" />
</ripple>
