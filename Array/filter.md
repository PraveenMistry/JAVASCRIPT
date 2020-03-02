This method receives a function as a parameter. And return a new array that contains all the elements of the array for which the filtering function passed as argument returns true.

`
const myAwesomeArray = [
  { id: 1, name: "john" },
  { id: 2, name: "Ali" },
  { id: 3, name: "Mass" },
  { id: 4, name: "Mass" },
]

myAwesomeArray.filter(element => element.name === "Mass")
//-------> Output : 0:{id: 3, name: "Mass"},
//                  1:{id: 4, name: "Mass"}
`