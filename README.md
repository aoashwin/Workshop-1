# Workshop.1
### Create an Android Application to display the welcome message and text to be displayed in Red color with center alignment. 
### Procedure:
### Step-1:
Use Android StudioIDE to create an Android application and name it as My
App under a package com.example.MyApp, with blank Activity. 
### Step-2:
Modify the default content of res/layout/activity_main.xml file to display the
required content and design the layout. 
### Step-3:
Don’t make any changes to MainActivity.java
### Step-4:
Run the code and launch the emulator to display the content in Android. 


### MainActivity.java
```java
package com.example.workshop1;
import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
public class MainActivity extends AppCompatActivity {
@Override
protected void onCreate(Bundle savedInstanceState) {
super.onCreate(savedInstanceState);
setContentView(R.layout.activity_main);
}
}
```
### activity_main.xml
```java
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Welcome"
        android:textSize="43sp"
        android:textColor="#EF2323"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```
### Output
![Screenshot (264)](https://user-images.githubusercontent.com/75236145/165342180-f9c57f40-cb44-4241-b14c-b7969a3a73b5.png)

### Result
Thus a Simple Android Application Create and to display the welcome message and text to be displayed in Red color with center alignment.

