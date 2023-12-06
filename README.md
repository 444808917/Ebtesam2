@@ -26,10 +26,11 @@ User's Manual:
TaskMate enables users to flexibly create and organize to-do lists, promote personal goal achievement and enhance daily productivity. It goes beyond the usual app, providing the ability to track task progress and analyze statistics directly, enhancing users' ability to evaluate and improve their performance.

Contributions:
•	shahid eali 
•	shahid nasir 
•	aibtisam murawaeiun
•	asma' ghasib 
-  asma' ghasib
-  shahid eali 
-  shahid nasir 
-  aibtisam murawaeiun



to contact us :
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

        <TextView
            android:id="@+id/tasksText"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:textStyle="bold"
            android:textColor="@android:color/black"
            android:layout_marginStart="16dp"
            android:layout_marginBottom="16dp"
            android:layout_marginTop="16dp"
            android:textSize="32sp"
            android:text="@string/tasks" />

        <androidx.recyclerview.widget.RecyclerView
            android:id="@+id/tasksRecyclerView"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_below="@id/tasksText"
            app:layoutManager="androidx.recyclerview.widget.LinearLayoutManager"
            android:nestedScrollingEnabled="true" />


    <com.google.android.material.floatingactionbutton.FloatingActionButton
        android:id="@+id/fab"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentEnd="true"
        android:layout_margin="32dp"
        android:backgroundTint="@android:color/holo_green_dark"
        android:src="@drawable/ic_baseline_add_24" />

</RelativeLayout>
