## Java Questions: 

“static”
Means that it is accessible by the Object not only through the instance of an object?  If so, do instances have access to it as well?
Static methods can be run as standalone methods.  No need to run with dot notation.

Is there a difference between a “property” (ie JavaScript) and a field ? 



## NOTES: 

All code contained inside class, also inside methods.

“Boilerplate”

```java

public class <same name as filename> {. //create a class with same name as file
	public static void main(String[] args) {. //create main method that runs all the stuffs.
		System.out.println(“Hello World!”);	
	}
}
```

To run in console: 

```java
javac <file.java> 
This compiles the code into an executable .class
java <file> // name of file without the .java
```

Java get time; 
Calendar.getInstance().get(Calendar.HOUR_OF_DAY) - gets an instance of the calendar object and then “gets” the hour of day - 24hr format-  


