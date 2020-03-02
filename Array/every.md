This method tests the array with a function passed as a parameter. It will return true if each element of the array match the test and false for the opposite.

`
const myAwesomeArray = ["a", "b", "c", "d", "e"]

myAwesomeArray.every(test => test === "d")
//-------> Output : false

const myAwesomeArray2 = ["a", "a", "a", "a", "a"]

myAwesomeArray2.every(test => test === "a")
//-------> Output : true

`