This method receives a function which has an accumulator and a value as an argument. It applies the function to the accumulator and each value in the array to return at the end just a single value.

`
const myAwesomeArray = [1, 2, 3, 4, 5]
myAwesomeArray.reduce((total, value) => total * value)
// 1 * 2 * 3 * 4 * 5
//-------> Output = 120
`
