# EntryManagementSoftware
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".Main3Activity">
    <TextView
        android:layout_width="match_parent"
        android:id="@+id/t3"
        android:textSize="40dp"

        android:textColor="#f8fffd"

        android:layout_height="wrap_content" />
    <EditText
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:id="@+id/e1"
        android:hint="USERNAME"
        android:textColorHint="#080b0b"
        android:layout_marginTop="10dp"
        android:background="#ffffff"></EditText>
    <EditText
        android:layout_width="match_parent"
        android:id="@+id/e2"
        android:layout_height="50dp"
        android:hint="EMAIL"
        android:textColorHint="#080b0b"
        android:layout_marginTop="10dp"
        android:background="#ffffff"></EditText>
    <EditText
    android:layout_width="match_parent"
    android:id="@+id/e3"
    android:layout_height="50dp"
    android:hint="MOBILENO"
    android:textColorHint="#080b0b"
    android:layout_marginTop="10dp"
    android:background="#ffffff"></EditText>
    <EditText
        android:layout_width="match_parent"
        android:id="@+id/e4"
        android:layout_height="50dp"
        android:hint="HOSTNAME"
        android:textColorHint="#080b0b"
        android:layout_marginTop="10dp"
        android:background="#ffffff"></EditText>
    <EditText
        android:layout_width="match_parent"
        android:id="@+id/e5"
        android:layout_height="50dp"
        android:hint="HOSTEMAIL"
        android:textColorHint="#080b0b"
        android:layout_marginTop="10dp"
        android:background="#ffffff"></EditText>
    <EditText
        android:layout_width="match_parent"
        android:id="@+id/e6"
        android:layout_height="50dp"
        android:hint="HOSTNO"
        android:textColorHint="#080b0b"
        android:layout_marginTop="10dp"
        android:background="#ffffff"></EditText>
    <Button
    android:layout_width="match_parent"
    android:id="@+id/button"
    android:text="Checkin"
    android:layout_height="50dp"
    ></Button>
    <Button
        android:layout_width="match_parent"
        android:id="@+id/button1"
        android:text="CHECK OUT"
        android:layout_height="50dp"
        ></Button>

</LinearLayout>
