# Style


    <!-- Base application theme. -->
    <style name="AppTheme" parent="Theme.AppCompat.Light.NoActionBar">
        <!-- Customize your theme here. -->
        <item name="colorPrimary">@color/colorPrimary</item>
        <item name="colorPrimaryDark">@color/colorPrimaryDark</item>
        <item name="colorAccent">@color/colorAccent</item>
        <item name="android:windowAnimationStyle">@style/CustomActivityAnimation</item>
    </style>


    <style name="CustomActivityAnimation" parent="@android:style/Animation.Activity">
        <item name="android:activityOpenEnterAnimation">@anim/slide_from_right</item>
        <item name="android:activityOpenExitAnimation">@anim/slideout_from_left</item>
        <item name="android:activityCloseEnterAnimation">@anim/slide_from_left</item>
        <item name="android:activityCloseExitAnimation">@anim/slideout_from_right</item>
    </style>





<<<<<<<<<<<<<<<<<<<<<<anim>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
    
    
    
    
    
    ////////////////#slide_from_right.xml////////////////////
   <?xml version="1.0" encoding="utf-8"?>
<set xmlns:android="http://schemas.android.com/apk/res/android"
    android:duration="250"
    android:interpolator="@android:anim/accelerate_decelerate_interpolator"
    >

    <translate
        android:fromXDelta="100%"
        android:toXDelta="0%"
        android:fromYDelta="0%"
        android:toYDelta="0%"
        />

</set>
  
    
    
    
    
    
    
    
     
    
     ////////////////#slideout_from_left.xml////////////////////
    <set xmlns:android="http://schemas.android.com/apk/res/android"
    android:duration="250"
    android:interpolator="@android:anim/accelerate_decelerate_interpolator"
    >

    <translate
        android:fromXDelta="0%"
        android:toXDelta="-100%"
        android:fromYDelta="0%"
        android:toYDelta="0%"
        />

</set>
   
    
    
    
    
    
    
    
    
    
    
    
     ////////////////#slide_from_left.xml////////////////////
     <?xml version="1.0" encoding="utf-8"?>
<set xmlns:android="http://schemas.android.com/apk/res/android"
    android:duration="250"
    android:interpolator="@android:anim/accelerate_decelerate_interpolator"
    >

    <translate
        android:fromXDelta="-100%"
        android:toXDelta="0%"
        android:fromYDelta="0%"
        android:toYDelta="0%"
        />

</set>
  
      
      
      
      
      
      
      
      
      
      
       ////////////////#slideout_from_right.xml////////////////////
       <?xml version="1.0" encoding="utf-8"?>
   <set xmlns:android="http://schemas.android.com/apk/res/android"
    android:duration="250"
    android:interpolator="@android:anim/accelerate_decelerate_interpolator"
    >
    
    

    <translate
        android:fromXDelta="0%"
        android:toXDelta="100%"
        android:fromYDelta="0%"
        android:toYDelta="0%"
        />
     </set>
    
        
        
        
        
        
        
    
<<<<<<<<<<<<<<<<<<<anim>>>>>>>>>>>>>>>>>>>>>>>>>>>>>


