# 🎉 Collection Framework in Java 🎉
![Collection Framework - Class Hierarchy](https://i0.wp.com/javaconceptoftheday.com/wp-content/uploads/2014/11/CollectionHierarchy.png?w=1300)

The Collection Framework in Java is a **🔑 fundamental 🔑** part of the Java language that allows developers to efficiently organize and manipulate groups of related objects. 😍

## 🌟 Collections Hierarchy 🌟

The Collections Framework in Java consists of several different types of interfaces and classes, each designed for a specific use case. These include:

| Interface  | Description                                                                                     |
|------------|-------------------------------------------------------------------------------------------------|
| Collection | 📦 The root of the collections hierarchy that defines the basic behavior of all collection classes |
| Set        | 🃏 A collection that contains no duplicate elements                                               |
| List       | 📜 An ordered collection (sometimes called a sequence)                                            |
| Queue      | 🚶‍♂️ A collection used to hold elements prior to processing                                          |
| Deque      | 🚪 A double-ended queue that supports insertion and removal at both ends                          |


## 🌟 Map Interface 🌟

The Map interface 🗺️ is also part of the Collection Framework, but it is not technically a collection. It represents a mapping between a key and a value.

## 🌟 Benefits of using Collection Framework 🌟

-   The Collection Framework provides a standard way to organize and manipulate collections of objects in Java.
-   It allows developers to choose the most appropriate data structure for their needs.
-   It reduces the amount of code required to work with collections.
-   It is highly efficient, providing excellent performance for large data sets.

So, start using the Collection Framework in Java today and organize your data like a pro! 🚀

# 🎉 Collection in Java 🎉

Collection in Java is the foundation of the Java Collections Framework. It provides a standard way to organize and manipulate groups of related objects.

## 💻 Examples

Let's take a look at some code examples to better understand how Collections work in Java.

### Creating a Collection

To create a Collection, you can use any of the Collection classes provided in Java. Here's an example of creating an ArrayList:

**java code**


``` java
import java.util.ArrayList;

public class Main {
    public static void main(String[] args) {
        ArrayList<String> names = new ArrayList<>();
        names.add("John");
        names.add("Doe");
        names.add("Smith");

        System.out.println(names);
    }
}
```

In this example, we imported the ArrayList class and created an ArrayList of Strings called `names`. We added three names to the list and printed out the contents of the list using `System.out.println()`.

### Iterating over a Collection

To iterate over the elements of a Collection, you can use a for-each loop. Here's an example of iterating over the names ArrayList we created earlier:

**java code**

``` java
import java.util.ArrayList;

public class Main {
    public static void main(String[] args) {
        ArrayList<String> names = new ArrayList<>();
        names.add("John");
        names.add("Doe");
        names.add("Smith");

        System.out.println(names);
    }
}
```
 

In this example, we used a for-each loop to iterate over the elements in the `names` ArrayList and print out each name to the console.

### Removing elements from a Collection

To remove an element from a Collection, you can use the `remove()` method. Here's an example of removing an element from the `names` ArrayList:

**java code**

``` java
import java.util.ArrayList;

public class Main {
    public static void main(String[] args) {
        ArrayList<String> names = new ArrayList<>();
        names.add("John");
        names.add("Doe");
        names.add("Smith");

        names.remove("Doe");

        System.out.println(names);
    }
}
```


In this example, we used the `remove()` method to remove the name "Bob" from the `names` ArrayList.

### 🌟 Conclusion

In conclusion, Collections in Java provide a powerful and flexible way to organize and manipulate groups of related objects. By using the Collection classes provided in Java, you can easily create, iterate over, and modify Collections to suit your needs. So start using Collections in your Java code today and make your code more organized and efficient! 🚀

# 🎉 Set in Java 🎉

![Java 8 - Sets in Java and how to use them](https://java8.info/images/sethierarchy.jpg)

In Java, a Set 🃏 is a collection that contains no duplicate elements. It provides several methods for adding, removing, and checking the contents of the Set 🕵️‍♀️.

## 💻 Examples

Let's take a look at some code examples to better understand how Sets work in Java.

### Creating a Set

To create a Set, you can use any of the Set classes provided in Java. Here's an example of creating a HashSet:

**java code**


``` java
import java.util.HashSet;
import java.util.Set;

public class Main {
    public static void main(String[] args) {
        Set<String> names = new HashSet<>();
        names.add("John");
        names.add("Doe");
        names.add("Smith");

        System.out.println(names);
    }
}
```



In this example, we imported the HashSet class and created a HashSet of Strings called `names`. We added three names to the Set and printed out the contents of the Set using `System.out.println()`.

### Checking if an Element is in a Set

To check if an element is in a Set, you can use the `contains()` method. Here's an example of checking if an element is in the `names` HashSet:

**java code**

``` java
import java.util.HashSet;
import java.util.Set;

public class Main {
    public static void main(String[] args) {
        Set<String> names = new HashSet<>();
        names.add("John");
        names.add("Doe");
        names.add("Smith");

        if (names.contains("Bob")) {
            System.out.println("🎉 Bob is in the set!");
        } else {
            System.out.println("😢 Bob is not in the set.");
        }
    }
}
```


In this example, we used the `contains()` method to check if the name "Bob" is in the `names` HashSet. If it is, we printed out "🎉 Bob is in the set!" to the console. If it is not, we printed out "😢 Bob is not in the set.".

### Removing Elements from a Set

To remove an element from a Set, you can use the `remove()` method. Here's an example of removing an element from the `names` HashSet:

**java code**

``` java
import java.util.HashSet;
import java.util.Set;

public class Main {
    public static void main(String[] args) {
        Set<String> names = new HashSet<>();
        names.add("John");
        names.add("Doe");
        names.add("Smith");

        names.remove("Smith");

        System.out.println(names);
    }
}
```


In this example, we used the `remove()` method to remove the name "Charlie" from the `names` HashSet.

### 🌟 Conclusion

In conclusion, Sets in Java provide a powerful and efficient way to store and manipulate groups of related objects with no duplicates. By using the Set classes provided in Java, you can easily create, check, and modify Sets to suit your needs. So start using Sets in your Java code today and make your code more organized and efficient! 🚀

# 📜 List in Java 📜

![Java List - List in Java | Scaler Topics](https://www.scaler.com/topics/images/list-and-its-use-cases_thumbnail.webp)

In Java, a List 📜 is an ordered collection, sometimes called a sequence. It allows duplicates and provides several methods for adding, removing, and accessing the contents of the List 📝.

## 💻 Examples

Let's take a look at some code examples to better understand how Lists work in Java.

### Creating a List

To create a List, you can use any of the List classes provided in Java. Here's an example of creating an ArrayList:

**java code**


``` java
import java.util.ArrayList;
import java.util.List;

public class Main {
    public static void main(String[] args) {
        List<String> names = new ArrayList<>();
        names.add("John");
        names.add("Doe");
        names.add("Smith");

        System.out.println(names);
    }
}
```

In this example, we imported the ArrayList class and created an ArrayList of Strings called `names`. We added three names to the List and printed out the contents of the List using `System.out.println()`.

### Accessing Elements in a List

To access an element in a List, you can use the `get()` method. Here's an example of accessing an element in the `names` ArrayList:

**java code**

``` java
import java.util.ArrayList;
import java.util.List;

public class Main {
    public static void main(String[] args) {
        List<String> names = new ArrayList<>();
        names.add("John");
        names.add("Doe");
        names.add("Smith");

        String secondName = names.get(1);
        System.out.println("Hello, " + secondName + "!");
    }
}
```

In this example, we used the `get()` method to access the second element in the `names` ArrayList (which is "Bob"). We then printed out a friendly greeting to Bob using `System.out.println()`.

### Removing Elements from a List

To remove an element from a List, you can use the `remove()` method. Here's an example of removing an element from the `names` ArrayList:

**java code**

``` java
import java.util.ArrayList;
import java.util.List;

public class Main {
    public static void main(String[] args) {
        List<String> names = new ArrayList<>();
        names.add("John");
        names.add("Doe");
        names.add("Smith");

        names.remove("Smith");

        System.out.println(names);
    }
}
```


In this example, we used the `remove()` method to remove the name "Charlie" from the `names` ArrayList.

### 🌟 Conclusion

In conclusion, Lists in Java provide a flexible and versatile way to store and manipulate sequences of related objects. By using the List classes provided in Java, you can easily create, access, and modify Lists to suit your needs. So start using Lists in your Java code today and make your code more organized and efficient! 🚀

# 🚶‍♂️ Queue in Java 🚶‍♀️

![Java Queue | PriorityQueue | ArrayDeque - java4coding](https://www.java4coding.com/contents/java/images/java-queue-0.png)

In Java, a Queue 🚶‍♂️ is a collection that is used to hold elements prior to processing. It follows the FIFO (First-In-First-Out) principle, meaning that the element that is added first is the one that will be removed first.

## 💻 Examples

Let's take a look at some code examples to better understand how Queues work in Java.

### Creating a Queue

To create a Queue, you can use any of the Queue classes provided in Java. Here's an example of creating a LinkedList:

**java code**


``` java
import java.util.LinkedList;
import java.util.Queue;

public class Main {
    public static void main(String[] args) {
        Queue<String> queue = new LinkedList<>();
        queue.add("Alice");
        queue.add("Bob");
        queue.add("Charlie");

        System.out.println(queue);
    }
}
```


In this example, we imported the LinkedList class and created a LinkedList of Strings called `queue`.


### Removing Elements from a Queue

To remove an element from a Queue, you can use the `remove()` or `poll()` method. Here's an example of removing an element from the `queue` LinkedList:

**java code**

``` java
import java.util.LinkedList;
import java.util.Queue;

public class Main {
    public static void main(String[] args) {
        Queue<String> queue = new LinkedList<>();
        queue.add("Alice");
        queue.add("Bob");
        queue.add("Charlie");

        String removedElement = queue.remove();
        System.out.println("Hello, " + removedElement + "!");

        // Alternatively, you can use the poll() method
        // String removedElement = queue.poll();
        // System.out.println("Hello, " + removedElement + "!");
    }
}
```

In this example, we used the `remove()` method to remove the first element in the `queue` LinkedList (which is "Alice"). We then printed out a friendly greeting to Alice using `System.out.println()`.

The `poll()` method works the same as `remove()`, except that it returns null if the Queue is empty.

### 🌟 Conclusion

In conclusion, Queues in Java provide a way to manage elements in a First-In-First-Out order. By using the Queue classes provided in Java, you can easily create, access, and remove elements from the Queue to suit your needs. So start using Queues in your Java code today and make your code more efficient! 🚀

# 🚪 Deque in Java 🚪

In Java, a Deque 🚪 is a double-ended queue that supports insertion and removal at both ends. It is pronounced "deck", short for "double-ended queue". Deques are similar to Queues, but they allow elements to be added and removed from both the front and the back of the queue.

## 💻 Examples

Let's take a look at some code examples to better understand how Deques work in Java.

### Creating a Deque

To create a Deque, you can use any of the Deque classes provided in Java. Here's an example of creating an ArrayDeque:

**java code**


``` java
import java.util.ArrayDeque;
import java.util.Deque;

public class Main {
    public static void main(String[] args) {
        Deque<String> deque = new ArrayDeque<>();
        deque.addFirst("Alice");
        deque.addLast("Bob");
        deque.addLast("Charlie");

        System.out.println(deque);
    }
}
```


In this example, we imported the ArrayDeque class and created an ArrayDeque of Strings called `deque`. We added three names to the Deque using the `addFirst()` and `addLast()` methods, and printed out the contents of the Deque using `System.out.println()`.

### Removing Elements from a Deque

To remove an element from a Deque, you can use the `removeFirst()` or `removeLast()` method. Here's an example of removing an element from the `deque` ArrayDeque:

**java code**

``` java
import java.util.ArrayDeque;
import java.util.Deque;

public class Main {
    public static void main(String[] args) {
        Deque<String> deque = new ArrayDeque<>();
        deque.addFirst("Alice");
        deque.addLast("Bob");
        deque.addLast("Charlie");

        System.out.println("Deque: " + deque);

        String removed = deque.removeFirst();
        System.out.println("Removed from Deque: " + removed);

        System.out.println("Updated Deque: " + deque);
    }
}
```


In this example, we used the `removeFirst()` method to remove the first element in the `deque` ArrayDeque (which is "Alice"). We then printed out a friendly greeting to Alice using `System.out.println()`.

### 🌟 Conclusion

In conclusion, Deques in Java provide a way to manage elements in a double-ended queue. By using the Deque classes provided in Java, you can easily create, access, and remove elements from the Deque to suit your needs. So start using Deques in your Java code today and make your code more versatile! 🚪

# Maps in Java 🗺️
![Java Collection Framework - The Map Interface](https://i0.wp.com/javaconceptoftheday.com/wp-content/uploads/2015/01/MapInterface.png?w=1300)

Maps in Java are a collection of key-value pairs, where each key is unique and maps to a corresponding value. Java provides several implementations of the Map interface, including HashMap, TreeMap, LinkedHashMap, and ConcurrentHashMap. Maps are used to store and manipulate data in a way that allows for efficient lookup and retrieval of values based on their associated keys.

## HashMap 🗃️

HashMap is an implementation of the Map interface in Java that uses a hash table to store its elements. It provides constant-time performance for basic operations such as adding, removing, and accessing elements. Here's an example of using HashMap in Java:

**java code**


``` java
import java.util.HashMap;
import java.util.Map;

public class HashMapExample {
    public static void main(String[] args) {
        Map<String, Integer> ageMap = new HashMap<>();
        ageMap.put("Alice", 30);
        ageMap.put("Bob", 25);
        ageMap.put("Charlie", 35);

        // Print all key-value pairs
        for (Map.Entry<String, Integer> entry : ageMap.entrySet()) {
            System.out.println("Name: " + entry.getKey() + ", Age: " + entry.getValue());
        }
    }
}
```

In this example, we create a new HashMap object called `ageMap` that maps strings (names) to integers (ages). We add three key-value pairs to the map using the `put` method, and then retrieve and print the ages of each person using the `get` method.

## TreeMap 🌳

TreeMap is another implementation of the Map interface in Java that uses a red-black tree to store its elements in sorted order. It provides guaranteed log(n) time cost for basic operations such as adding, removing, and accessing elements. Here's an example of using TreeMap in Java:

**java code**


``` java
import java.util.Map;
import java.util.TreeMap;

public class TreeMapExample {
    public static void main(String[] args) {
        Map<String, Integer> ageMap = new TreeMap<>();
        ageMap.put("Alice", 30);
        ageMap.put("Bob", 25);
        ageMap.put("Charlie", 35);

        // Print all key-value pairs
        for (Map.Entry<String, Integer> entry : ageMap.entrySet()) {
            System.out.println("Name: " + entry.getKey() + ", Age: " + entry.getValue());
        }
    }
}
```


In this example, we create a new TreeMap object called `ageMap` that maps strings (names) to integers (ages). We add three key-value pairs to the map using the `put` method, and then retrieve and print the ages of each person using the `get` method. The elements are automatically sorted in ascending order based on the keys.

## LinkedHashMap 🧩

LinkedHashMap is another implementation of the Map interface in Java that maintains the order in which its elements were added. It provides constant-time performance for basic operations such as adding, removing, and accessing elements, but slightly slower than HashMap due to the additional overhead of maintaining the insertion order. Here's an example of using LinkedHashMap in Java:

**java code**


``` java
import java.util.LinkedHashMap;
import java.util.Map;

public class LinkedHashMapExample {
    public static void main(String[] args) {
        Map<String, Integer> ageMap = new LinkedHashMap<>();
        ageMap.put("Alice", 30);
        ageMap.put("Bob", 25);
        ageMap.put("Charlie", 35);

        // Print all key-value pairs
        for (Map.Entry<String, Integer> entry : ageMap.entrySet()) {
            System.out.println("Name: " + entry.getKey() + ", Age: " + entry.getValue());
        }
    }
}
```


        

# Summary - Collection Framework in Java 📦

In Java, the Collection Framework 📦 is a set of classes and interfaces that provides an organized way of storing and manipulating objects. The Collection Framework defines a hierarchy of interfaces and classes that represent different types of collections, such as Lists, Sets, and Queues.

#### 🔑 Key Interfaces and Classes

The Collection Framework is built around a few key interfaces and classes:

-   📦`Collection`: The root interface in the Collection Framework that defines the basic behavior of all collection classes.
-  📜 `List`: An ordered collection (sometimes called a sequence).
-  🃏 `Set`: A collection that contains no duplicate elements.
-   🚶‍♂️`Queue`: A collection used to hold elements prior to processing.
-   🚪`Deque`: A double-ended queue that supports insertion and removal at both ends.
-   🗺️`Map`: A collection that maps keys to values.📜


# 📦 Applications of Collection Framework in Java 📦

The Collection Framework in Java 📦 is widely used in many applications to store and manipulate data. The framework provides a set of classes and interfaces that can be used to manage collections of objects. Here are some examples of how the Collection Framework can be applied in Java.

### 📊 Data Analysis

The Collection Framework can be used for data analysis tasks, such as counting occurrences of items in a dataset or computing the average of a set of values. For example, you could use a HashMap to count the number of occurrences of each item in a list, or a TreeSet to sort a set of values in ascending order.

### 🖥️ User Interfaces

The Collection Framework can be used to store and manage data in user interfaces. For example, you could use a List to store the items in a drop-down menu, or a Set to store the items in a multi-select list. You could also use a Map to store the settings for a user's preferences.

### 🎲 Game Development

The Collection Framework can be used in game development to manage game data. For example, you could use a List to store the players in a game, or a Queue to manage the order of player turns. You could also use a Map to store the scores of each player.

### 🏭 Enterprise Applications

The Collection Framework can be used in enterprise applications to manage data in databases or data warehouses. For example, you could use a List to store the results of a database query, or a Set to store unique values in a column. You could also use a Map to store the data in a key-value pair format.

# 📦 Collection Framework in Java -  Quiz 📦

Test your knowledge of the Collection Framework in Java with these tricky and interesting multiple choice questions! 🤔💭

1.  Which interface extends the Collection interface and guarantees that its elements will be stored in ascending order?

-   A. List 📜
-   B. Queue 🚶‍♂️
-   C. Set 🃏
-   D. SortedSet 🗃️

<details> <summary>Answer</summary> D: SortedSet 🗃️ </details>

2.  Which of the following is not a class in the Collection Framework?

-   A. HashSet 🔴
-   B. ArrayList 📚
-   C. LinkedMap 🔗
-   D. PriorityQueue 🏆

<details> <summary>Answer</summary> C: LinkedMap 🔗 </details>

3.  What is the difference between a List and a Set?

-   A. A List guarantees that its elements will be stored in order, while a Set does not.
-   B. A List can contain duplicates, while a Set cannot. 🚫🔁
-   C. A List can only store objects, while a Set can store any type of data. 🆎
-   D. A List is a collection of key-value pairs, while a Set is a collection of values.

<details> <summary>Answer</summary> B: A List can contain duplicates, while a Set cannot. 🚫🔁 </details>

4.  What is the time complexity of adding an element to a HashSet?

-   A. O(1) ⚡
-   B. O(n) 🐌
-   C. O(log n) 📈
-   D. O(n log n) 📉

<details> <summary>Answer</summary> A: O(1) ⚡ </details>

5.  Which of the following classes in the Collection Framework allows you to store elements in a last-in, first-out (LIFO) order?

-   A. List 📜
-   B. Set 🃏
-   C. Queue 🚶‍♂️
-   D. Stack 📚🔝

<details> <summary>Answer</summary> D: Stack 📚🔝 </details>

6.  Which interface in the Collection Framework is used to represent a collection of key-value pairs?

-   A. Map 🗺️
-   B. List 📜
-   C. Set 🃏
-   D. Queue 🚶‍♂️

<details> <summary>Answer</summary> A: Map 🗺️ </details>

7.  Which of the following is not a method in the Collection interface?

-   A. add() ➕
-   B. remove() ❌
-   C. contains() 🔍
-   D. get() 🔎

<details> <summary>Answer</summary> D: get() 🔎 </details>

8.  Which class in the Collection Framework allows you to sort its elements in natural order or by a Comparator?

-   A. ArrayList 📚
-   B. HashSet 🔴
-   C. TreeMap 🌳
-   D. PriorityQueue 🏆

<details> <summary>Answer</summary> C: TreeMap 🌳 </details>

9.  Which of the following collection classes in Java is used to maintain a sorted order of its elements?

- a. HashSet 🚫 
- b. ArrayList 📜 
- c. PriorityQueue 🏆 
- d. TreeMap 🌳

Answer: d: TreeMap 🌳

10.  Which of the following collection classes in Java implements the Deque interface and allows null elements to be added?

- a. HashSet 🚫 
- b. LinkedList 🐇 
- c. TreeSet 🌳 
- d. ArrayDeque 📦

Answer: d:  ArrayDeque 📦

