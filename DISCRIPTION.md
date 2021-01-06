# assignment-one
##Answers:
Assignment I
QUESTION 1 What changes are made when you add a second Activity to your app by choosing File > New > Activity and an Activity template? Choose one: A. The second Activity is added as a Java class. You still need to add the XML layout file. B. The second Activity XML layout file is created and a Java class added. You still need to define the class signature. C. The second Activity is added as a Java class, the XML layout file is created, and the AndroidManifest.xml file is changed to declare a second Activity. D. The second Activity XML layout file is created, and the AndroidManifest.xml file is changed to declare a second Activity.
Answer C,The second Activity is added as a Java class, the XML layout file is created, and the AndroidManifest.xml file is changed to declare a second Activity.
QUESTION 2 What happens if you remove the android:parentActivityName and the <meta-data> elements from the second Activity declaration in the AndroidManifest.xml file? Choose one: A. The second Activity no longer appears when you try to start it with an explicit Intent. B. The second Activity XML layout file is deleted. C. The Back button no longer works in the second Activity to send the user back to the main Activity.
D. The Up button in the app bar no longer appears in the second Activity to send the user back to the parent Activity.
Answer D, The Up button in the app bar no longer appears in the second Activity to send the user back to the parent Activity.
Question 3 Which constructor method do you use to create a new explicit Intent? Choose one:
A. new Intent()
B. new Intent(Context context, Class<?> class)
C. new Intent(String action, Uri uri)
D. new Intent(String action)
Answer B,new Intent(Context context, Class<?> class)
QUESTION 4
In the HelloToast app homework, how do you add the current value of the count to the Intent?
Choose one:
A. As the Intent data
B. As the Intent TEXT_REQUEST
C. As an Intent action
D. As an Intent extra
Answer D,As an Intent extra
QUESTION 5
In the HelloToast app homework, how do you display the current count in the second "Hello"
Activity? Choose one:
A. Get the Intent that the Activity was launched with.
B. Get the current count value out of the Intent.
C. Update the TextView for the count.
D. All of the above.
Answer B,Get the current count value out of the Intent. And
C,Update the TextView for the count.
Assignment II
QUESTION 1
If you run the homework app before implementing onSaveInstanceState(), what happens if you
rotate the device? Choose one:
A. The EditText no longer contains the text you entered, but the counter is preserved. B. The counter is reset to 0, and the EditText no longer contains the text you entered. C. The counter is reset to 0, but the contents of the EditText is preserved.
D. The counter and the contents of the EditText are preserved.
Answer B, The counter is reset to 0, and the EditText no longer contains the text you entered.
QUESTION 2
What Activity lifecycle methods are called when a device-configuration change (such as rotation) occurs? Choose one: A. Android immediately shuts down your Activity by calling onStop().Your code must restart the Activity. B. Android shuts down your Activity by calling onPause(), onStop(), and onDestroy(). Your code must restart the Activity. C. Android shuts down your Activity by calling onPause(), onStop(), and onDestroy(), and then starts it over again, calling onCreate(), onStart(), and onResume().
D Android immediately calls onResume().
Answer C,Android shuts down your Activity by calling onPause(), onStop(), and onDestroy(), and then starts it over again, calling onCreate(), onStart(), and onResume().
QUESTION 3 When in the Activity lifecycle is onSaveInstanceState() called? Choose one: A. onSaveInstanceState() is called before the onStop() method. B. onSaveInstanceState() is called before the onResume() method. C. onSaveInstanceState() is called before the onCreate() method. D. onSaveInstanceState() is called before the onDestroy() method.
Answer A, onSaveInstanceState() is called before the onStop() method.
QUESTION 4 Which Activity lifecycle methods are best to use for saving data before the Activity is finished or destroyed? Choose one:
A. onPause() or onStop()
B. onResume() or onCreate() C. onDestroy() D. onStart() or onRestart()
Answer A, onPause() or onStop()
