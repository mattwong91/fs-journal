# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | var, const, and let |

02. What is the definition of a function?

    > | Functions are subprograms that perform specific tasks |

03. What are the `SOLID` principles?

    > | Five design principles for object oriented programming. They are: Single Responsibility Principle, Open-Close Principle, Liskov Substitution Principle, Interface Segregation Principle, Dependency Inversion Principle |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | find the index for the pineapple value, and then use use the splice method to remove 1 element beginning at that index Ex: fruit.splice(index, 1) |

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > | them.friends.push(you) | you.friends.push(them)

06. Give an example of a JavaScript `Conditional`:

    > | if(fruits == 'banana')  { return true }|

07. What is the main difference between `parameters` and `arguments`?

    > | parameters are the values that a function uses during execution. Arguments are the values supplied to the function when invoking|

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | Add breakpoints and use line by line stepover. Use dev tools to invoke functions, check definitions of objects, arrays, etc. You can also use git branches to test new solutions without losing previously written code. |

09. What is the difference between a `primitive` value and a `reference` value?

    > | reference values are changeable and primitive values cannot be changed. you cannot assign the primitive value of 0 to be 1, but you can assign a reference to be the primitive value 1 instead of 0.|

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for(let i = -100; i <= 100; i++ ) { console.log(i) }
