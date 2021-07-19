**Q:** 
```js
const shapes = ['square', 'circle', 'triangle', 'rectangle']
```
How can we log rectangle to the console using the array above and what is the relationship between an length of an array and the end of an array.

> (A)

```js
console.log(shapes[3])
```

The length of an array is determined by how many index elements are withing the array. Each element is assigned an index number which is determined by its position and starts from index 0. The last index within an array will always be 1 less than it's length

**Q:**

```

let square = {
    sides: 4,
    equalSides: true
}
```


what would you call the example above?, name it's parts and how would we log true to the console using this example


> (A)

```

console.log(square.equalSides)
```

> (A) The above example is known as an object. square is the variable that is being given the value of everything withing the {}, which is the object. sides and equalSides are both keys which are given then given the values, 4 and true respectively.

**Q:**

```js
const shapes = [
    {
    name: 'square',
    sides: 4
    }
    {
    name: 'triangle',
    sides: 3
     } 
]
```
Log the number 3 to the console and explain the path using array and objects

> (A)

```js

console.log(shapes[1].sides)
```

> (A) Shapes is an array that is given the value of 2 objects. The first object is at index 0 and the second is at index 1. Since we were asked to log 3, we have to know that path which starts at Shapes then leads you to index 1,

```
Shapes[1]
```
> (A) , and then the key sides which has the value of 3, 
```js 
shape[1].sides
```
> (A) Once we have our path we can simply log it to the terminal.  




