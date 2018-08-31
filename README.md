# Javascript30-15
An alternate approach to #15 localStorage and event delegation tutorial by wesbos in his Javascript30 edition.

## Changes:
* Instead of calling `populateList` every time a new item is added to the list, a method is defined to append only the newly added list item to the unordered list.
* Altered `populateList`. Instead of changing the `innerHTML`, the altered version appends the list elements for each iteration through the `items` array.
* Added functionality to uncheck all list elements that are checked.
* Added functionality to clear the list
