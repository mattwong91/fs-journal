# JavaScript

Create console groups
console.group('group_name')
console.groupEnd()

ternary operator is '?' example: `boolean_expr ? 'true_value' : 'false_value'`

Objects and arrays are references. So if we copy a new variable from a object, they will point to the same point in memory.
`personCopy = person` is assigning the same pointer to 'personCopy' as 'person'

key value pairs can be removed and added to an object
`delete person.age` and `person.favoriteColor = 'blue'`

spread operator `...person` dumps all key-value pairs of the 'person' object
`const personCopy = {...person}` 'breaking reference'

finding a random array index: `Math.floor(Math.random() * array.length)`
`array.find()` returns first element that fufills condiiton.
`array.filter()` returns an array of elements that fit condition