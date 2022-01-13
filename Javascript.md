# JS methods📚

## Array.prototype.forEach()  
The forEach() method executes a provided function once for each array element.

## Array.prototype.find()
The find() method returns the value of the first element in the provided array that satisfies the provided testing function. If no values satisfy the testing function, undefined is returned.

## Array.prototype.filter()  
The filter() method creates a new array with all elements that pass the test implemented by the provided function.

## Array.prototype.some()  
The some() method tests whether at least one element in the array passes the test implemented by the provided function. 
It returns true if, in the array, it finds an element for which the provided function returns **true; otherwise it returns false.**
It doesn't modify the array.

## Array.prototype.includes()  
The includes() method determines whether an array includes a certain value among its entries, returning **true or false** as appropriate.

 [.some() vs .includes()comparison](https://hianna.tistory.com/403)

## Array.prototype.flat()
The flat() method creates a new array with all sub-array elements concatenated into it recursively up to the specified depth.
```Javascript
const arr1 = [0, 1, 2, [3, 4]];
// expected output: [0, 1, 2, 3, 4]
const arr2 = [0, 1, 2, [[[3, 4]]]];
console.log(arr2.flat(2));
// expected output: [0, 1, 2, [3, 4]]
```
