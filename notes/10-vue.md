# Vue

Vue uses components
`HTML`, `JavaScript`, and `CSS` are all within a `.vue` file

Use double curly brackets to inject javascript directly into the HTML `{{ }}`

Scoped scss so that the styling only affects the file it is contained within.

In order to make variables or functions/methods accessible to the HTML you need to put it into a `return` object within the `setup` function.
Anything within `setup` is `private`, and then if they are in the `return` object they become public.

Using logger util instead of console log

Use `ref()` and insert the value of the variables into the function. That way all event listeners and emitters are setup automatically and it will update the DOM accordingly when the value of that variable changes

Data in the AppState is declared as a key value pair within the object passed to the `reactive` function.
Import those into the `setup()` function within a component

Bring a variable from the AppState using `computed()`. Computed returns a ref()
An example is 
`cheese: computed( () => {return Appstate.cheese} )` 
OR 
`cheese: computed( () =>  Appstate.cheese )`

To get the value stored in a `ref()` variable you need to use `.value`

Can inject a component into another one, and it becomes a child. We can pass an iterated object in and it becomes the prop of the child component
Think of props like a parameter, and in the parent component, you pass an argument into the prop.

Remember to remove `.js` from `.vue` file imports in the `<script>` tag