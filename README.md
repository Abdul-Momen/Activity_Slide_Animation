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
