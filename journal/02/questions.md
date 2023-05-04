# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | let, var, const |

02. What is the definition of a function?

    > | the logic contained between the curly brackets {} |

03. What are the `SOLID` principles?

    > | single responsibility, open-close, Liskov substitution, interface segregation, dependency inversion |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | filter? |

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

    > | type "them" in top green brackets and "you" in the bottom ones |

06. Give an example of a JavaScript `Conditional`:

    > | if (age < 18) text = "too young to vote legally" |

07. What is the main difference between `parameters` and `arguments`?

    > | parameters are similar to variable names, whereas arguments specify what the values are |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | debugger that loads page in stages to help isolate problems |

09. What is the difference between a `primitive` value and a `reference` value?

    > | primitive values are immutable, reference values can by mutated |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | let CurrentNumber = -100
        if (CurrentNumber <= 101) {
        return CurrentNumber
        CurrentNumber++
        } |
