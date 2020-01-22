# CoreJavaProjectQuestions
```
1. Create package called “com.exam.exceptions”.

Create 2 custom exceptions  classes called NegativeNumberException and
ZeroNumberException.
write a class called ExceptionExample with main method. Accept a
number from user and print “Positive” if the number is positive. Or
throw NegativeNumberExeption if number is negative and
ZeroNumberException if number is zero.

2. Encapsulation : Create a package called “com.exam.encapsulation”.
Create a class called student with following properties/fields with
getter setters.

Student Name
Student Age
Department

  Create a StudentDetails class with main method. Create a new
student object and assign name , age and department. Print out these
details with System.out.println().


3. Create a interface called fruit with 2 methods isSweet and
isPoisonous. Create 2 classes called Apple and PoisonBerry which
implement this interface and override the methods.


4. Create a class called Department. It should have 3 constructors.  it
will have 3 properties/fields deptName, id, location.

1st constructor does not take any arguments.
2nd constructor takes dept name and id as parameters.
3rd constructor takes leapt name , id and location as parameters

 5. Writing your own exception class

Create a new class whose name should end with Exception like ClassNameException. This is a convention to differentiate an exception class from regular ones.
Make the class extends one of the exceptions which are subtypes of the java.lang.Exception class. Generally, a custom exception class always extends directly from the Exception class.
Create a constructor with a String parameter which is the detail message of the exception. In this constructor, simply call the super constructor and pass the message.
