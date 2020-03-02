The method applies a function to each element of the array and then flatten the result into an array. It combines flat() and map() in one function.

`
const myAwesomeArray = [[1], [2], [3], [4], [5]]

myAwesomeArray.flatMap(arr => arr * 10)
//-------> Output : [10, 20, 30, 40, 50]

// With .flat() and .map()
myAwesomeArray.flat().map(arr => arr * 10)
//-------> Output : [10, 20, 30, 40, 50]
`