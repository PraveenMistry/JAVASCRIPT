This method receives a function as a parameter. It sorts the elements of an array and returns it.

`
const myAwesomeArray = [5, 4, 3, 2, 1]

// Sort from smallest to largest
myAwesomeArray.sort((a, b) => a - b)
//-------> Output : [1, 2, 3, 4, 5]

// Sort from largest to smallest
myAwesomeArray.sort((a, b) => b - a)
//-------> Output : [5, 4, 3, 2, 1]
`