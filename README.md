# List<E> class

## Properties

- length => returns total number of elements in given list.

- reversed => returns an iterable object with the list elements in reverse order.

- isEmpty => returns boolean if given list is empty or not.

- first => returns first element from given list.

- last => returns last element from given list.


## Methods
- add(E value) → void
  => adds value to the end of this list, extending the length by one.

- clear() → void
  => removes all objects from this list; the length of the list becomes zero.

- insert(int index, E element) → void
  => inserts element at position index in this list.

- contains()
  => is used to check if an element occurs in a list. This method takes one parameter and returns a boolean value indicating whether or not that item is found in the list.

- forEach()

## Example
List<String> names = ["Mohammed", Ahmed", "Ali"];

names.add("Afrah");   // ["Mohammed", Ahmed", "Ali", "Afrah"]
names.insert(2, "Abeer");  // ["Mohammed", Ahmed", "Abeer", "Ali", "Afrah"]
bool isFound = names.contains("Ali");  // true
names.clear();  // []
