This method receives a function as a parameter and will apply it to the array. It returns the index of an element found and which satisfies the test function passed as an argument or -1 if none satisfies it.

`
const myAwesomeArray = [
  { id: 1, name: "john" },
  { id: 2, name: "Ali" },
  { id: 3, name: "Mass" },
]

myAwesomeArray.findIndex(element => element.id === 3)
//-------> Output : 2

myAwesomeArray.findIndex(element => element.id === 7)
//-------> Output : -1
`
