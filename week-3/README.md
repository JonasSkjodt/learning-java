Week 3 notes:

##ArrayList

/**
 * imports
 */

<br /> import java.util.ArrayList; // ArrayList<>
<br /> import java.util.Collections; // Collection.sort();

 /***
 * Standard ArrayList.
 * Example:
 *
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
 ***/

 /***
 *
 * liste.get(0);
 * Get the (number) from the array list
 * Example:
 */ 

  
 /***
 *
 * liste.set(0, 9);
 * set the number 9 in the array list on spot number (0)
 * Example:
 */

 /***
 *
 * liste.remove(0);
 * Remove the specific string or int from the ArrayList
 * Example:
 */ 

 /***
 *
 * liste.clear();
 * Clear the array list of all <integer> or <String>
 * Example:
 */ 


  
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
 ***/


 /***
 *
 * Collections.sort(liste);                                    
 * sorterer alfabetiskt i string eller fra 0 og op i int
 * Example:
 *                                   
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
 ***/
