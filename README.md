# prog_mobile1_xml_qr_code
# 1. Tugas Pemrograman Mobile 1 | Pembuatan XML QR CODES
## Ulfiyah Syifayani - 312110281
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingTop="@dimen/activity_horizontal_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin">

    <Button
        android:id="@+id/button"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="QR Code Scan"
        android:layout_alignParentBottom="true"/>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:layout_centerVertical="true">


        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Nama" />
        <TextView
            android:id="@+id/textViewNama"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="xyz"
            android:textAppearance="@style/TextAppearance.AppCompat.Large"/>

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Kelas" />

        <TextView
            android:id="@+id/textViewKelas"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="xyz"
            android:textAppearance="@style/TextAppearance.AppCompat.Large"/>

        <TextView

            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Nim" />

        <TextView
            android:id="@+id/TextViewNim"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="xyz"
            android:textAppearance="@style/TextAppearance.AppCompat.Large"/>

    </LinearLayout>

</RelativeLayout>
