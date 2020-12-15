# Fibonocci-Android-app

Create an Android Application, written in Kotlin, that displays a Fibonacci number to the user by following these steps:

1. Create a module that contains the logic to generate the nth Fibonacci number for a given index.  Include the following:

•	An interface / protocol defining a method that takes an index as a parameter and returns the Fibonacci number for that index
•	Test cases that cover implementation

2. Build a native app to that uses the module from step 1 display the Fibonacci numbers.  It has the following requirements:

•	The app should launch and display the Fibonacci number at index 0.
•	Every second that elapses, the app should increment the index and show the next corresponding Fibonacci number.
•	After reaching F(10) decrement the index each second until reaching F(0).
•	The app should then begin counting up again, and so on.


Keep in mind

*If the app goes into the background it should remember the last number displayed and should resume where it left off upon entering the foreground.

*The Fibonacci sequence from [0,10] is (0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55).
 
*Use best design, development, conventions, and methodology per your knowledge, and document the thought process / decisions.
