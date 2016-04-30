# PLProject6

**Problem 1:**

* Addition: `(let (a 2) (+ 8 a))` -> `10`
* Subtraction: `(let (a 2) (- 8 a))` -> `6` 
* Multiplication: `(let (a 2) (* 8 a))` -> `16`
* Division: `(let (a 2) (/ 8 a))` -> `4`

For the boolean evaluations, calls will only return a value if the input has the correct number of arguments.  For example `(if 0 1 2)` will return `2`, but `(if 1 2)` will return `Invalid number of arguments`

**Problem 2:**

Our program supports the evaluation of the following input:
`(car '(1 2 3))`  
