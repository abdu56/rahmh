<inset xmlns:android="http://schemas.android.com/apk/res/android" android:insetLeft="@dimen/abc_button_inset_horizontal_material" android:insetRight="@dimen/abc_button_inset_horizontal_material" android:insetTop="@dimen/abc_button_inset_vertical_material" android:insetBottom="@dimen/abc_button_inset_vertical_material">
<ripple android:color="?android:colorControlHighlight">
<item>
<selector>
<item android:state_enabled="false">
<shape android:shape="rectangle">
<corners android:radius="@dimen/abc_control_corner_material"/>
<solid android:color="?android:colorButtonNormal"/>
<padding android:left="@dimen/abc_button_padding_horizontal_material" android:top="@dimen/abc_button_padding_vertical_material" android:right="@dimen/abc_button_padding_horizontal_material" android:bottom="@dimen/abc_button_padding_vertical_material"/>
</shape>
</item>
<item>
<shape android:shape="rectangle">
<corners android:radius="@dimen/abc_control_corner_material"/>
<solid android:color="?android:colorAccent"/>
<padding android:left="@dimen/abc_button_padding_horizontal_material" android:top="@dimen/abc_button_padding_vertical_material" android:right="@dimen/abc_button_padding_horizontal_material" android:bottom="@dimen/abc_button_padding_vertical_material"/>
</shape>
</item>
</selector>
</item>
</ripple>
</inset>
