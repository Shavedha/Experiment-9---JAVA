# Experiment-8---JAVA
## AIM
To create java program to add, retrieve and remove the element from the ArrayList.
## ALGORITHM
1. Declare a main method using public class Main.
2. Create an ArrayList named "list"
3. Add elements to ArrayList using the command "Arraylistname.add()".
4. Retrive an element from the ArrayList using "get" command and print the same.
5. Remove the element from the ArrayList using "remove" command and print the same.
6. Print the updated list and end the program.

## PROGRAM
```
import java.util.ArrayList;

public class Main {
    public static void main(String[] args) {
        ArrayList<String> list = new ArrayList<>(); // Create an ArrayList

        // Adding elements to the ArrayList
        list.add("Apple");
        list.add("Banana");
        list.add("Cherry");
        list.add("Durian");

        System.out.println("ArrayList: " + list);

        // Retrieve element at index 2
        String retrievedElement = list.get(2);
        System.out.println("Retrieved element at index 2: " + retrievedElement);

        // Remove element at index 1
        String removedElement = list.remove(1);
        System.out.println("Removed element at index 1: " + removedElement);

        System.out.println("Updated ArrayList: " + list);
    }
}
```
## OUTPUT
<img width="422" alt="image" src="https://github.com/Shavedha/Experiment-8---JAVA/assets/93427376/baab5b85-b4a8-4ed4-a859-49de7fd856ed">

## RESULT
Thus a program is created to add,retrive and remove an element from an ArrayList.
