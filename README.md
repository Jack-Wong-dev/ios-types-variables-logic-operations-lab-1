# Types Variables Logic and Operations Lab

## Instructions for lab submission

1. Fork the assignment repo
1. Clone your Fork to your machine
1. Complete the lab
1. Push your changes to your Fork
1. Submit a Pull Request back to the assignment repo
1. Paste a link to of your Fork on Canvas and submit

## 1. Which data type would be the best to use for recording the total balance of an online shopping cart?

Double (and Float)

***
## 2. Which of the following variable declarations is **incorrect**?

```swift
let isClosed: Bool = false

let version: Double = 3.0

let emotion: String = ":)"

let grade: Char = "a"
```
let grade: Char = "a", should be 
let grade: Character = "a"
***
## 3. Simplify the following using a calculator:

1 + 4 * 2 / 2 + 27


7
***


## 4. Which of the following are true? State all that apply.

```swift
17 % 4 == 1        //True

25 % 4 != 1        //False

81 % 9 != 840 % 2  //False

(14 % 2 < 4) || (243 % 13 > 2) || (52 % 3 > 5)        //True
```
17 % 4 == 1        is True      

25 % 4 != 1         is False

81 % 9 != 840 % 2    is False

(14 % 2 < 4) || (243 % 13 > 2) || (52 % 3 > 5)        is True 


***
## 5. Which of the follow is true?

a)
```swift
let numOne = 4.0
let numTwo = 4.0
let a = numOne == numTwo
```
True

b)
```swift
let numThree = 24/5
let numFour = 24.0/5.0
let b = numThree == numFour
```
False.  
* Can't divide integers 

c)
```swift
let numFive = 24%5
let numSix = 24.0%5.0
let c = numFive == numSix
```
False
* Can't use mod on float/double variables

d)
```swift
let numSeven = 4.0 + 1.2
let numEight = 5.0 + .2
let d = numSeven == numEight
```
False
* Incorrect notation of decimals.  Should be 0.2
***
## 6. What is the final value of i?

```swift
var i = 0
i = 5
i += 3
i *= 2
i %= 3
i -= 3
```
-2
