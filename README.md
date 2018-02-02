# Happy-Birthday
Code for Happy Birthday Android App
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.android.happybirthday.MainActivity">

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="centerCrop"
        android:src="@drawable/spanish" />
        *Centers image pulled from "drawable" folder and fills the screen with said image.*
    <TextView
        android:id='@+id/happy_birthday'
        *establishes id for this TextView so it can be called back later*
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentTop="true"
        android:layout_alignParentRight="true"
        *Lines 22 and 23 allow this TextView to sit at the top-right of screen.*
        android:text="Hey! It's your birthday!!!"
        android:paddingRight="8dp"
        android:paddingTop="8dp"
        *Lines 26 and 27 allow for the Textview to be shifted from the edge from 8 density pixels from the right and the top.*
        android:textSize="18sp"
        *Line 29 makes size of text 18 scaled pixels.*
        android:fontFamily="sans-serif-light"
        android:textColor="#000000" />
        *Line 33 makes colors font Black.*

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Don't be dramatic!"
        android:layout_alignParentRight="true"
        *Line 39 establishes TextView on right side of screen.*
        android:layout_below="@id/happy_birthday"
        *Line 41 sits this TextView right below previously established TextView.*
        android:textSize="18sp"
        *Line 43 makes size of text 18 scaled pixels.*
        android:paddingRight="8dp"
        android:fontFamily="sans-serif-light"
        android:textColor="#000000"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="From, Alejandro."
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true"
        *Lines 53 and 54 allow TextView to sit at bottom-right of screen.*
        android:textSize="24sp"
        android:background="#000000"
        *Line 57 makes TextView background Black.*
        android:fontFamily="sans-serif-light"
        android:textColor="#FFFFFF" />
        *Line 60 colors font White.*

</RelativeLayout>
