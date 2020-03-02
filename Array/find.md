This method receives a function as an argument and will apply it to the array. It returns the value of an element found in the array and which satisfies the test function. Otherwise, it returns undefined.

`
const myAwesomeArray = [
  { id: 1, name: "john" },
  { id: 2, name: "Ali" },
  { id: 3, name: "Mass" },
]

myAwesomeArray.find(element => element.id === 3)
//-------> Output : {id: 3, name: "Mass"}

myAwesomeArray.find(element => element.id === 7)
//-------> Output : undefined

`
