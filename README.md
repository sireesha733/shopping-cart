# shopping-cart
android studio
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@color/black">
    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">

        <ImageView
            android:id="@+id/womendress1"
            android:layout_width="wrap_content"
            android:layout_height="400dp"
            android:layout_gravity="center"
            android:layout_marginTop="14dp"
            android:src="@drawable/BlackGIO" />




    </RelativeLayout>

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">


        <TextView
            android:id="@+id/Title"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_marginLeft="130dp"
            android:layout_marginTop="14dp"
            android:layout_toRightOf="@+id/womendress1"
            android:text="BLACK GIO"
            android:textColor="#FCFFFE"
            android:textSize="28sp"></TextView>

        <TextView
            android:id="@+id/louis"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_below="@+id/Title"
            android:layout_gravity="center"
            android:layout_marginLeft="4dp"
            android:layout_marginTop="22dp"
            android:layout_toRightOf="@+id/womendress1"
            android:text="GIORGIO ARMANI line blended slimfit"
            android:textColor="#9F989B"
            android:textSize="20sp"></TextView>

        <TextView
            android:id="@+id/vitton"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_below="@+id/louis"
            android:layout_gravity="center"
            android:layout_marginLeft="17dp"
            android:layout_marginTop="21dp"
            android:layout_toRightOf="@+id/womendress1"
            android:text=" ₹104,000"
            android:textColor="#E8ECEF"
            android:textSize="25sp"></TextView>
    </RelativeLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">
        <Button
            android:id="@+id/button1"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Add to Cart"
            android:layout_marginRight="25dp"
            android:backgroundTint="#F3F7F8"
            android:textColor="#131201"
            android:layout_gravity="rightHorizontal"
            android:layout_marginTop="14dp"
            android:textSize="20sp">
        </Button>

        <Button
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_gravity="rightHorizontal"
            android:layout_marginLeft="55dp"
            android:layout_marginTop="14dp"
            android:backgroundTint="#EFF4F4"
            android:text="Buy now"
            android:textColor="#1B1801"
            android:textSize="20sp"></Button>
    </LinearLayout>
</LinearLayout>
