# Activity-lifecycle-and-state

## Task 1

When app is started

<img src="screenshots/activitiesTask1.png">

## Task 2

When using the app

<img src="screenshots/ActivitiesTasks.gif" width="250" height="450">

<img src="screenshots/activitiesTask2.png">

<img src="screenshots/activities2.gif">

When app is close

<img src="screenshots/activitiesTask2.png">

## Task 3

Save and restore the Activity instance state

<img src="screenshots/activitieslifeor.png"  width="500">

<img src="screenshots/activitiesor2.png"  width="500">

## Coding Challenge

Shopping list app

<img src="screenshots/Activitylifecycle%20challenge.gif" width="250" height="450">

<img src="screenshots/Activitylifecycle%20challenge%20rotate.gif" width="500">

## Homework

Counter homework

<img src="screenshots/homework1.gif" width="250" height="450">

<img src="screenshots/homeworks.png" width="500">

When Rotating the device the current state of the app is saved

<img src="screenshots/homework2.gif" width="500">

## Answer these questions

### Question 1

If you run the homework app before implementing onSaveInstanceState(), what happens if you rotate the device?

Ans - The counter is reset to 0, but the contents of the EditText is preserved.

### Question 2

What Activity lifecycle methods are called when a device-configuration change (such as rotation) occurs? 

Ans -  Android shuts down your Activity by calling onPause(), onStop(), and onDestroy(), and then starts it over again, 
calling onCreate(), onStart(), and onResume().

### Question 3

When in the Activity lifecycle is onSaveInstanceState() called?

Ans - onSaveInstanceState() is called before the onStop() method.

### Question 4

Which Activity lifecycle methods are best to use for saving data before the Activity is finished or destroyed?

Ans - onPause() or onStop()


