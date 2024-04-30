# What is Array in Js?
### An array in JavaScript is a type of global object that is used to store data. Arrays consist of an ordered collection or list containing zero or more data types, and use numbered indices starting from 0 to access specific items.
# Array Methods!
## Method push()
The push() method adds new items to the end of an array.

The push() method changes the length of the array.

The push() method returns the new length.

Syntax:

array.push(item1, item2, ..., itemX)
![alt text](image.png)
## Method pop()
The pop() method removes (pops) the last element of an array.

The pop() method changes the original array.

The pop() method returns the removed element.

Syntax:

array.pop()

Parameters:

NONE
## Method unshift()
The unshift() method adds new elements to the beginning of an array.

The unshift() method overwrites the original array.

Syntax:

array.unshift(item1, item2, ..., itemX)
![alt text](image-1.png)
## Method shift()
The shift() method removes the first item of an array.

The shift() method changes the original array.

The shift() method returns the shifted element.

Syntax:

array.shift()
![alt text](image-2.png)
## Method toString()
The toString() method returns a string with array values separated by commas.

The toString() method does not change the original array.

Note

Every JavaScript object has a toString() method.

The toString() method is used internally by JavaScript when an object needs to be displayed as a text (like in HTML), or when an object needs to be used as a string.

Normally, you will not use it in your own code.

![alt text](image-3.png)
## Method indexOf()
The indexOf() method returns the first index (position) of a specified value.

The indexOf() method returns -1 if the value is not found.

The indexOf() method starts at a specified index and searches from left to right (from the given start postion to the end of the array).

By default the search starts at the first element and ends at the last.

Negative start values counts from the last element (but still searches from left to right).
![alt text](image-4.png)
## Method include()
The includes() method returns true if an array contains a specified value.

The includes() method returns false if the value is not found.

The includes() method is case sensitive.
![alt text](image-5.png)
## Method concat()
The concat() method concatenates (joins) two or more arrays.

The concat() method returns a new array, containing the joined arrays.

The concat() method does not change the existing arrays.
![alt text](image-6.png)
## Method slice()
The slice() method returns selected elements in an array, as a new array.

The slice() method selects from a given start, up to a (not inclusive) given end.

The slice() method does not change the original array.
![alt text](image-7.png)
## Method splice()
The splice() method adds and/or removes array elements.

The splice() method overwrites the original array.
![alt text](image-8.png)
## Callback methods in Js
## What is Callback in Js?
A JavaScript callback is a function which is to be executed after another function has finished execution. A more formal definition would be - Any function that is passed as an argument to another function so that it can be executed in that other function is called as a callback function.

![alt text](image-9.png)
## Callback method map()
The map() method of Array instances creates a new array populated with the results of calling a provided function on every element in the calling array.
![alt text](image-10.png)
## Callback method forEach()
The forEach() method is an iterative method. It calls a provided callbackFn function once for each element in an array in ascending-index order. Unlike map() , forEach() always returns undefined and is not chainable. The typical use case is to execute side effects at the end of a chain.
![alt text](image-11.png)
## Callback method find()
The find() method of Array instance returns the first elment of the provided array.
![alt text](image-12.png)
## Callback method filter()
In JavaScript, the filter() method is an iterative method that calls a callback function once for each element in an array. If the callback function returns true, it includes that element in the return array.
![alt text](image-13.png)
## Callback method toSorted()
The toSorted() method of Array instances is the copying version of the sort() method. It returns a new array with the elements sorted in ascending order.
![alt text](image-14.png)
