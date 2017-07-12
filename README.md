# hello-world
I want to build an app which deals with our onsite car battery installation services, technicians, Inventories, Scraps, Accounting, Ware House
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:layout_behavior="@string/appbar_scrolling_view_behavior"
    tools:showIn="@layout/activity_main"
    tools:context="ae.batterymobile.www.mathsucks.MainActivity">


    TextView ToatalTextView;
    EditText percentageTxt;
    EditText numbertxt;

    <TextView
        android:id="@+id/TotalTextView"
        android:layout_width="188dp"
        android:layout_height="60dp"
        android:text="0"
        android:textAlignment="center"
        android:textSize="50sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.013" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="67dp"
        android:layout_height="42dp"
        android:text="%"
        android:textSize="30sp"
        app:layout_constraintHorizontal_bias="0.981"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        tools:layout_editor_absoluteY="148dp" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="62dp"
        android:layout_height="51dp"
        android:lineSpacingExtra="10sp"
        android:text="Of"
        android:textAlignment="center"
        android:textSize="30sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.452" />

    <TextView
        android:id="@+id/textView3"
        android:layout_width="144dp"
        android:layout_height="55dp"
        android:background="@color/colorAccent"
        android:text="What is"
        android:textAlignment="center"
        android:textSize="30sp"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        tools:layout_editor_absoluteY="77dp" />

    <EditText
        android:id="@+id/editText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:hint="Enter Number"
        android:inputType="numberDecimal"
        android:textAlignment="center"
        app:layout_constraintHorizontal_bias="0.502"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        tools:layout_editor_absoluteY="274dp" />

    <EditText
        android:id="@+id/editText2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:hint="Enter Percentage"
        android:inputType="numberDecimal"
        android:textAlignment="center"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintHorizontal_bias="0.502"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.316" />

    <Button
        android:id="@+id/button"
        android:layout_width="203dp"
        android:layout_height="47dp"
        android:background="@color/colorAccent"
        android:backgroundTintMode="add"
        android:text="CALCULATE"
        android:textStyle="bold"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        tools:background="?android:attr/colorPressedHighlight"
        tools:layout_editor_absoluteY="432dp" />

</android.support.constraint.ConstraintLayout>
