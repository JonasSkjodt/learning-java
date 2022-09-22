## Notes
1: LinkedLists


## LinkedLists continued

Insertion: inserts in front of list.

Traversal: What is on every part of the list, from a->b b->c c->d etc.


## Arrays

```java
//decleration of an array
int[] grades = new int[7]; // erklæring, instantiering og initialisering (angiv størrelsen af arrayen i []
grades[0] = -3; // insert different integers to a specific position of the array
grades[1] = 0;
grades[2] = 2;
grades[3] = 4;
grades[4] = 7;
grades[5] = 10;
grades[6] = 12;
// læse:
int grade = grades[3]; // declare a variable of position 3?
System.out.println(grade); // print position 3

//iteration of array

// for loop
int[] numbers = new int[10];
:
for (int i = 0; i < numbers.length; i++) {
  System.out.println(numbers[i]); // læse
  numbers[i] = numbers[i] + 1; // skrive
}

// to an arrayliste
List<Integer> numbers = new ArrayList<>();
:
for (int i = 0; i < numbers.size(); i++) {
  System.out.println(numbers.get(i)); // læse
  numbers.set(i, numbers.get(i) + 1); // skrive
}

// for-each loop with the same as above
int[] numbers = new int[10];
:
for (int number : numbers) {
  System.out.println(number); // læse
  // skrive: vi mangler en index (position)
}

//for-each loop with arraylist
List<Integer> numbers = new ArrayList<>();
:
for (int number : numbers) {
  System.out.println(number); // læse
  // skrive: vi mangler en index (position)
}
```
