# Android Certified Application Developer
(Exam Code: AND-401)
Exam Sample

### Q1.What method you should override to use Android’s menu which is placed on the action bar?

* A. onCreateOptionsMenu()
* B. onCreateMenu()
* C. onMenuCreated()
* D. onMenuCreated()
Answer: A

### Q2.What Activity method you use to retrieve a reference to an Android view by using the id
attribute of a resource XML?

* A. findViewByReference(int id)
* B. findViewById(int id)
* C. retrieveResourceById(int id)
* D. findViewById(String id)
Answer: B

### Q3.Which of the following is not an Android component (i.e. a point from which the system can enter your application)?
* A. Service
* B. Activity
* C. Layout
* D. Content Provider
Answer: C
### Q4.During an Activity life-cycle, what is the first callback method invoked by the system?
* A. onStop()
* B. onStart()
* C. onCreate()
* D. onRestore()
Answer: C
### Q5.Which configuration file holds the permission to use the internet?
* A. Layout file
* B. Property file
* C. Java source file
* D. Manifest file
Answer: D

### Q6.What does the following line of code achieve? `Intent intent = new Intent(FirstActivity.this, SecondActivity.class );`
* A. Creates a hidden Intent.
* B. Creates an implicit Intent.
* C. Create an explicit Intent.
* D. Starts an activity.
Answer: C

### Q7. Which of the following is NOT a valid usage for Intents?
A. Activate and Activity.
B. Activate a Service.
C. Activate a Broadcast receiver.
D. Activate a SQLite DB Connection.
Answer: D

### Q8. Which of the following is not a valid Android resource file name?
A. mylayout.xml
B. myLayout.xml
C.my_layout.xml
D.mylayout1.xml
Answer: B

### Q9. Which one of the following is not a valid name for process state?
A. Bound
B. A Visible
C. Foreground
D. Background
Answer: A

### Q10. What is the role of the R.java file in an Android application project?
A. It contains all resource IDs allowing the developer to reference them from the code using
integers.
B. It contains instructions to build the Android application project.
C. It contains information about content providers of the Android application.
D. It contains the target SDK version number.
Answer: A

### Q11. What is a correct statement about an XML layout file?
A. A layout PNG image file.
B. A file used to draw the content of an Activity.
C. A file that contains all application permission information.
D. A file that contains a single activity widget.
Answer: B

### Q12. Which folder contains the Android project Java files?
A. res
B. manifests
C. assets
D. java
Answer: D

### Q13.Which file specifies the minimum required Android SDK version your application supports?
A. main.xml
B. R.java
C. strings.xml
D. build.gradle
Answer: D

### Q14. What is the parent class of all Activity widgets?
A. ViewGroup
B. Layout
C. View
D. Widget
Answer: C

### Q15. What is the name of the class used by Intent to store additional information?
A. Extra
B. Parcelable
C. Bundle
D. DataStore
Answer: C

### Q16.Which of the following is not included in the Android application framework?
A. WindowManager
B. NotificationManager
C. DialerManager
D. PackageManager
Answer: C

### Q17.Which of the following is NOT true about the R.java file?
A. It is auto-generated during the build of the project.
B. It is used by developers to access any resource through an ID.
C. It can be modified manually to change the ID of a resource.
D. It contains resource IDs for all resources in your /res/ folder.
Answer: C

### Q18.You can create a custom view by extending class Activity.
A. True
B. False
Answer: B

### Q19.Which of these files contains text values that you can use in your application?
A. AndroidManifest.xml
B. res/Text.xml
C.res/layout/Main.xml
D. res/values/strings.xml
Answer: D

### Q20. What does the Android project folder “res/” contain?
A. Java Activity classes
B. Resource files
C. Java source code
D. Libraries
Answer: B

Q21.What does this code do?
Intent intent = new Intent();
intent.setAction(Intent.ACTION_VIEW);
intent.setData(android.net.Uri.parse("http://www.androidatc.com"));
startActivity(intent);
A. Starts a sub-activity.
B. Starts a service.
C. Sends results to another activity.
D. Starts an activity using an implicit intent.
Answer: D
Q22.Which method should you use to start a sub-activity?
A. startActivity(Intent intent)
B. startActivityForResult(Intent intent)
C. startService(Intent intent)
D. startSubActivity(Intent intent)
Answer: B
Q23.Which of the following packages does not have classes needed for Android network
connections?
A. java.net
B. org.apache.http
C. android.location
D. android.net
Answer: C
Q24.What is the second layer from top called in the following diagram of Android’s Architecture
A. Applications layer.
B. Application framework.
C. Linux kernel.
D. Android runtime.
Answer: B
Q25.Which of the following tools creates certificates for signing Android applications?
A. adb
B. logcat
C. keytool
D. certgen
Answer: C
Which Android permission you should add to allow your application to read the device’s address
book?
A. READ_ADDRESS_DATA
B. READ_PHONE_STATE
C. READ_PHONE_CONTACTS
D. READ_CONTACTS
Answer: D
Q26.Which of the following methods is called in an Activity when another activity gets into the
foreground?
A. onStop()
B. onPause()
C. onDestroy()
D. onExit()
Answer: B
Q27.Which of the following attributes is used to set an activity screen to landscape orientation?
A. screenorientation = landscape
B. screenOrientation=”landscape”
C. android:ScreenOrientation=“landscape”
D. android:screenOrientation=”landscape”
Answer: D
Q28.What is not true about the AndroidManifest.xml file?
A. It declares the views used within the application.
B. It declares user permissions the application requires.
C. It declares application components.
D. It declares hardware and software features used within the application.
Answer: A
Q29.If your application is throwing exception android.content.ActivityNotFoundException, which
of the following could resolve the problem?
A. Create a new sub-class of the View class
B. Create a new broadcast receiver
C. Create the activity layout
D. Add the activity to AndroidManifest.xml]
Answer: D
Q30.Consider the following code:
Intent intent = new Intent();
intent.setAction(Intent.ACTION_VIEW);
intent.setData(android.net.Uri.parse("http://www.androidatc.com"));
startActivity(intent);
Which of the following is correct about the code above?
A. It sends a result to a new Activity in a Bundle.
B. It will not compile without adding the INTERNET permission the Manifest file.
C. It starts any activity in the application that has a WebView in its layout.
D. When it is executed, the system starts an intent resolution process to start the right Activity.
Answer: D
Q31.Which of the following Android View sub-classes uses the WebKit rendering engine to
display web pages?
A. PageView
B. WebView
C. MapView
D. HttpClient
Answer: B
Q32.Which of the following lines of codes adds zoom controls to a WebView?
A. webView.getSettings().setBuiltInZoomControls(true);
B. webView.getSettings().setZoomControls(true);
C. webView.getZoomSettings().setControls(CONTROLS.enabled);
D. Zoom controls are included by default in WebViews
Answer: A
Q33.Which of the following best explains the Android option menus?
A. It is a popup menu that displays a list of items in a vertical list anchored to the view that
invoked the menu.
B. It is a floating menu that appears when the user performs a long-click on an element. It
provides actions that affect the selected content or context frame.
C. It is the primary collection of menu items for an activity where you should place actions that
have a global impact on the app, such as "Search," "Compose email," and "Settings”.
D. It is a type of List Activity with predefined headers and footers for special commands.
Answer: C
Q34.Which of the following best explains the Android context menus?
A. It is a popup menu displays a list of items in a vertical list that's anchored to the view that
invoked the menu.
B. It is a floating menu that appears when the user performs a long-click on an element. It
provides actions that affect the selected content or context frame.
C. It is the primary collection of menu items for an activity. It's where you should place actions
that have a global impact on the app, such as "Search," "Compose email," and "Settings".
D. It is a sub-menu of an options menu item.
Answer: B
Q35.Which of the following applies a context menu on a ListView? (Choose two)
A. ListView lv = getListView();
lv.registerForContextMenu()
B. ListView lv= getListView();
registerForContextMenu(lv);
C. ListView lv = (ListView) findViewById(R.id.list_view_id);
registerForContextMenu(lv)
D. getListView().setConextMenuEnabled(true)
Answer: B & C
Q36.Consider the following code :
@Override
public void onCreateContextMenu(ContextMenu menu, View v,
ContextMenuInfo menuInfo) {
super.onCreateContextMenu(menu, v, menuInfo);
menu.setHeaderTitle("Menu");
AdapterContextMenuInfo cmi = (AdapterContextMenuInfo) menuInfo;
menu.add(1, cmi.position, 0, "Open file");
menu.add(2, cmi.position, 0, "Save file");
}
Which of the following best explains the code above?
A. The code inflates an xml file into menu items.
B. The code creates menu items for context menu programmatically.
C. The code assign actions to menu items.
D. The code Opens a menu resource file, modifies it, and saves the changes.
Answer: B
Q37.Which Which of the following does NOT correctly describe interface
android.widget.Adapter?
A. It is an object that acts as a bridge between a View and underlying data for that view.
B. It provides access to the data items.
C. It provides access to deprecated ListView methods.
D. It is responsible for making a View for each item in the data set.
Answer: C
Q38.When is the intent resolution process triggered?
A. When the system receives an implicit intent to start an activity.
B. When an explicit intent starts a service.
C. When the system receives an explicit intent to start an activity.
D. When the application calls method startAcitivyIntentResolution.
Answer: A
Q39.Which of the following applies to the onDraw() method of class View? (Choose two)
A. It must be overridden if a customized drawing of a view is required.
B. It takes two parameters: a Canvas and a View.
C. It takes one parameter of type Canvas.
D. It uses the Canvas parameter to draw the border of the activity that contains it.
Answer: A & C
Q40.What is the location of the APK generated by the build system of Android Studio?
A. app/build/apk
B. app/apks
C. app/build/outputs/apk
D. app/intermediates/outputs/apk
Answer: C
Q41.Which of the following statements is NOT correct about Android fragments?
A. Multiple fragments can be combined in a single activity.
B. The life-cycle of a fragment is totally independent of the activity hosting it.
C. Fragments have their own life-cycle.
D. You can add/remove fragments to and an activity dynamically; i.e. while the activity is
running.
Answer: B
Q42.Which of the following statements is incorrect about Android Device Monitor in Android
Studio?
A. You can display a list of currently running threads and select one to check its stack trace.
B. It can add dynamically Google SDK libraries to the Android image running on the emulator.
C. You can forcibly execute garbage collection and check the present heap usage status.
D. You can do simulations of network zone speed and bandwidth limitations.
Answer: B
Q43.Which of the following is incorrect about intents?
A. They can be used to start an Activity.
B. They can be used to start a service.
C. They can be used to start database insertion.
D. They can be used to start a dialog-themed activity.
Answer: C
Q44.Method onDraw() of class android.view.View has the following signature:
A. public void onDraw(Color)
B. public void onDraw(Canvas)
C. public boolean onDraw(Canvas)
D. public Canvas onDraw()
Answer: B
Q45.To create a blank Wear activity in Android Studio, the project should have a minimum SDK
version >= 20.
A. True
B. False
Answer: A
Q46.To create a customized Adapter for a compound list item layout , you should:
A. Extend class android.widget.Adapter or any of its descendants then override method
getView()
B. Extend class android.widget.ListView or any of its descendants, then override method
getView()
C. Extend class android.widget.AbsAdapter or any of its descendants, then override method
getView()
D. Extend class android.widget.Adapter or any of its descendants, then override method
getAdapterView()
Answer: A
Q47.When publishing an update to your application to the market, the following must be taken
into consideration:
A. The package name must be the same, but the .apk may be signed with a different private
key.
B. The package name does not have to be the same and the .apk can be signed with a different
private key.
C. The package name must be the same and the .apk must be signed with the same private
key.
D. The package name does not have to be the same, but the .apk must be signed with the
same private key.
Answer: C
Q48.Which of these is the incorrect method for an Application to save local data?
A. Extend PreferencesActivity and save in an XML file.
B. Save as a file in the local file system.
C. Save in the database using SQLite.
D. Save in the hash table file using the Dictionary class.
Answer: D
Q49.Which of the following lines of code is used to pass a value to the next activity?
A.Intent i = new Intent(this,newActivity);
i.addExtra(“test”);
startActivity(i);
B. Intent i = new Intent(this,newActivity);
i.putValue(“test”);
startActivity(i);
C. Intent i = new Intent(this,newActivity);
i.putValue(“value1”,“test”);
startActivity(i);
D. Intent i = new Intent(this,newActivity);
i.putExtra(“value1”,“test”);
startActivity(i);
Answer: D
Q50.Which of the following lines of code sets the entire Activity window as a WebView?
A. WebView webview = new WebView(this);
webview.setAsWindow;
B. setContentView(R.layout.webview);
C. WebView webview = new WebView(this);
setContentView(webview);
D.setContentView(“http://www.androidatc.com”);
Answer: C
Q51.Consider the following the code :
public boolean onCreateOptionsMenu(Menu menu) {
 MenuInflater inflater = getMenuInflater();
 inflater.inflate(R.menu.game_menu, menu);
 return true;
}
Which of the following is true about the code above?
A. The code is auto generated and should not be edited.
B. This method handles clicks and assign actions to menu items.
C. This function inflates an XML file in the res/menu folder into menu items.
D. This method inflates an XML file in the res/layout folder into layout.
Answer : C
Q52.Which of the following is a rule that developers must always follow when writing multithreaded
Android applications? (Choose two)
A. A worker thread must not be created from inside the UI thread.
B. Each UI thread must not create more than one worker thread.
C. The UI thread must never be blocked.
D. The Android UI must not be accessed from outside the UI thread.
Answer: C & D
Q53.Which of the following is NOT true about class AsyncTask?
A. It must be used by sub-classing it.
B. It must be created on the UI thread.
C. Its sub-class override at least two methods: doInBackground, onPostExecute.
D. It uses three generic types.
Answer: C
Q54.When the user clicks on an action item in the action bar, which of the following Activity
methods does the system call?
A. onOptionsItemSelected()
B. onOptionsItemClicked()
C. onActionButtonSelected()
D. onActionBarItemSelected()
Answer: A
Q55.Gradle is the build system used in Android Studio. It builds, tests, runs, and packages your
apps.
A. True
B. False
Answer: A
Q56.Which of the following is NOT correct about the Gradle build system of Android Studio?
A. The Gradle build file is called build.gradle.
B. Gradle supports generating only one build variant.
C. Gradle uses the Groovy syntax to configure the build.
D. A build is configured by using elements provided by the Android plugin for Gradle.
Answer: B
Q57.To use the material design features of Android 5.0, you should set the
android:targetSdkVersion attribute to 20 in your application’s build.gradle file.
A. True
B. False
Answer: B
Q58.Which UI does the following code builds?
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android=http://schemas.android.com/apk/res/android
android:layout_width="match_parent"
android:layout_height="match_parent"
android:orientation="vertical" >
<LinearLayout
android:layout_width="match_parent"
android:layout_height="wrap_content"
android:orientation="horizontal" >
<TextView
android:id="@+id/textView1"
android:layout_width="wrap_content"
android:layout_height="wrap_content"
android:text="Name:" />
<EditText
android:id="@+id/editText1"
android:layout_width="match_parent"
android:layout_height="wrap_content"
android:layout_weight="1"
android:ems="10" />
</LinearLayout>
<Button
android:id="@+id/button1"
android:layout_width="wrap_content"
android:layout_height="wrap_content"
android:text="Post" />
</LinearLayout>
A. An edit text to the left of a text view and a button beneath it
B. An edit text to the right of a text view and a button to the right of the text view
C. An edit text to the right of a text view and a button beneath them
D. A text view, an edit text beneath it and the button beneath the edit text
Answer: C
