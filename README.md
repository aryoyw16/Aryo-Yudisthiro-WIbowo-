# Aryo-Yudisthiro-WIbowo-
TUGAS 2 - Pemrograman Mobile
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity"
    android:background="@drawable/bg_gradient">


    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_margin="20dp"
        android:fontFamily="sans-serif"
        android:gravity="center"
        android:text="SELAMAT DATANG DI UNIVERSITAS ESA UNGGUL
                               Program Studi Teknik Informatika - Fakultas Ilmu Komputer"
        android:textColor="#142DBD"
        android:textSize="25sp"/>

    <androidx.cardview.widget.CardView
        android:layout_width="150dp"
        android:layout_height="150dp"
        app:cardCornerRadius="250dp"
        android:layout_gravity="center">


        <ImageView
            android:layout_width="150dp"
            android:layout_height="219dp"
            android:scaleType="centerCrop"
            android:src="@drawable/aryoyw"/>

    </androidx.cardview.widget.CardView>


<LinearLayout
    android:layout_width="match_parent"
    android:orientation="vertical"
    android:layout_height="wrap_content">

    <TextView
        android:layout_width="wrap_content"
        android:layout_margin="15dp"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:textColor="#090909"
        android:textSize="23dp"
        android:text="Aryo Yudisthiro Wibwowo">

    </TextView>
</LinearLayout>

    <androidx.appcompat.widget.LinearLayoutCompat

        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_marginLeft="34dp"
        android:layout_marginRight="1dp"
        android:text="NIM                 : 20190801296"
        android:textColor="#090909"
        android:textSize="16sp"/>

    </androidx.appcompat.widget.linearlayoutcompat>

    <androidx.appcompat.widget.LinearLayoutCompat
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"

        android:layout_gravity="center"
        android:layout_marginLeft="34dp"
        android:layout_marginRight="1dp"
        android:text="HOBBY           : playing basketball and playing games"
        android:textColor="#090909"
        android:textSize="16sp"/>
    </androidx.appcompat.widget.LinearLayoutCompat>

    <androidx.appcompat.widget.LinearLayoutCompat
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_marginLeft="34dp"
        android:layout_marginRight="1dp"
        android:text="PEKERJAAN : Pelajar/Mahasiswa"
        android:textColor="#090909"
        android:textSize="16sp"/>

    </androidx.appcompat.widget.LinearLayoutCompat>


    <androidx.appcompat.widget.LinearLayoutCompat
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_marginLeft="34dp"
        android:layout_marginRight="1dp"
        android:text="STATUS         : Belum Menikah "
        android:textColor="#090909"
        android:textSize="16sp"/>

    </androidx.appcompat.widget.LinearLayoutCompat>


</LinearLayout>



BACKGROUND

<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="rectangle">

    <gradient
        android:startColor="#D57C1E"
        android:centerColor="#2F8DB8"
        android:endColor="#062AF3"
        android:angle="270"
        />

