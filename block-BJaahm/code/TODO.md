1. Construct a function intersection that compares input arrays and returns a new array with elements found in all of the inputs. You can only use reduce method to do this.

```js
function intersection(arr1 ,arr2 ,arr3) {
   let common = arr1.filter((elm)=>arr2.includes(elm));
     return  common.filter((elm)=>arr3.includes(elm))  ;
} 

// Test
console.log(
  intersection(
    [5, 10, 15, 20],
    [15, 88, 1, 5, 7],
    [1, 10, 15, 5, 20]
  )
); // should log: [5, 15]
```

2. Construct a function `union` that compares input arrays and returns a new array that contains all elements. If there are duplicate elements, only add it once to the new array. Preserve the order of the elements starting from the first element of the first input array. You can only use reduce method to do this.

```js
function union(arr , arr1, arr2) {
   let finalArr = arr.concat(arr1 , arr2);
 return finalArr.filter((item, 
            index) => finalArr.indexOf(item) === index);
}

// Test
console.log(
  union([5, 10, 15], [15, 88, 1, 5, 7], [100, 15, 10, 1, 5])
);
// should log: [5, 10, 15, 88, 1, 7, 100]
```
