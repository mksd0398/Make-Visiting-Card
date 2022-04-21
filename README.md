# Make-Visiting-Card
VTU AAD Subject Part A First program Make Visiting Card
### For Reference : Project Code

change these files in your project

UI: default created : activity_main.xml

```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView"
        style="@style/head"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Company Name"
        app:layout_constraintBottom_toBottomOf="@+id/imageView2"
        app:layout_constraintEnd_toStartOf="@+id/imageView2"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/imageView2" />

    <View
        android:id="@+id/view"
        android:layout_width="0dp"
        android:layout_height="1sp"
        android:layout_marginStart="20dp"
        android:layout_marginTop="10dp"
        android:layout_marginEnd="20dp"
        android:background="@color/black"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView2" />

    <TextView
        android:id="@+id/textView2"
        style="@style/body"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:text="Name"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/view" />

    <TextView
        android:id="@+id/textView3"
        style="@style/body"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:text="Job Title"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView2" />

    <TextView
        android:id="@+id/textView4"
        style="@style/body"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:text="+91 374637485"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView3" />

    <TextView
        android:id="@+id/textView5"
        style="@style/body"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:text="23 street, Newal Road USA"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView4" />

    <TextView
        android:id="@+id/textView6"
        style="@style/body"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="20dp"
        android:layout_marginEnd="20dp"
        android:text="zydg@gmail.coms"
        app:layout_constraintBottom_toBottomOf="@+id/textView7"
        app:layout_constraintEnd_toStartOf="@+id/textView7"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/textView7" />

    <TextView
        android:id="@+id/textView7"
        style="@style/body"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:text="www.fdhs.com"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView5" />

    <TextView
        android:id="@+id/textView8"
        style="@style/body"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="20dp"
        android:layout_marginEnd="20dp"
        android:text="Fax Details"
        app:layout_constraintBottom_toBottomOf="@+id/textView7"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toEndOf="@+id/textView7"
        app:layout_constraintTop_toTopOf="@+id/textView7" />

    <ImageView
        android:id="@+id/imageView2"
        android:layout_width="130dp"
        android:layout_height="130dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@android:drawable/ic_menu_mapmode"
        app:layout_constraintStart_toEndOf="@id/textView"/>

</androidx.constraintlayout.widget.ConstraintLayout>
```

Theme: append this to themes.xml

*note: style will go under resource tag*

```xml
<style name="head" parent="Theme.MakeVisitingCard">
	<item name="android:textSize">20sp</item>
</style>
<style name="body" parent="Theme.MakeVisitingCard">
	<item name="android:textSize">16sp</item>
</style>
```

Project link: 

Now Run the program
