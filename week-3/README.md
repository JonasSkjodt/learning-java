Week 3 notes:

##ArrayList

```java
/**
 * imports
 */

import java.util.ArrayList; // ArrayList<>
import java.util.Collections; // Collection.sort();
```

```java
 /***
 * Standard ArrayList.
 * Example:
 */

import java.util.ArrayList;
  public class Main {
    public static void main(String[] args) {
      ArrayList<String> liste = new ArrayList<String>();
      cars.add("Volvo");
      cars.add("BMW");
      cars.add("Ford");
      cars.add("Mazda");
      System.out.println(liste);
    }
  }
```

```java
 /***
 *
 * liste.get(0);
 * Get the (number) from the array list
 * Example:
 */ 
```

```java
 /***
 *
 * liste.set(0, 9);
 * set the number 9 in the array list on spot number (0)
 * Example:
 */
```

```java
 /***
 *
 * liste.remove(0);
 * Remove the specific string or int from the ArrayList
 * Example:
 */ 
```

```java
 /***
 *
 * liste.clear();
 * Clear the array list of all <integer> or <String>
 * Example:
 */ 
```


```java
 /***
 *
 * liste.size(); count the amount of things in the array
 * Example:
 */ 
 
 public class Main {
  public static void main(String[] args) {
    ArrayList<String> cars = new ArrayList<String>();
    cars.add("Volvo");
    cars.add("BMW");
    cars.add("Ford");
    cars.add("Mazda");
    for (int i = 0; i < cars.size(); i++) {
      System.out.println(cars.get(i));
    }
  }
}
```

```java
 /***
 *
 * Collections.sort(liste);                                    
 * sorterer alfabetiskt i string eller fra 0 og op i int
 * Example:
 */
 
 public class arraylistz {
    public static void main(){
        ArrayList<Integer> liste = new ArrayList<>();
        liste.add(3);
        liste.add(9);
        liste.add(10);
        Collections.sort(liste);
        for (int i : liste) {
          System.out.println(i);
        }
    }
}
 ```
