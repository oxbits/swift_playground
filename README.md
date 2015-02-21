# swift_playground

Swift Playground: Exploring and Evaluating Swift Code in a Playground (copy &amp; paste)

These are the examples from:

https://developer.apple.com/library/ios/recipes/xcode_help-source_editor/chapters/ExploringandEvaluatingSwiftCodeinaPlayground.html

On the above page the code examples are in images, which is very annoying.
Here I provide them so you can save time by copying and pasting:

```
// Playground - noun: a place where people can play

import UIKit

var str = "Hello, playground"

let triple: Int -> Int = {
    (number: Int) in
    
    let result = 3 * number
    number
    
    return number
}
triple(3)


let listOfNumbers = 1...5
var sum = 0
for atNum in listOfNumbers {
    sum += atNum
}
sum


var j = 2
for var i = 0; i < 5; ++i {
    j += j * i
}
j

```

\* Swift is a proprietary language, Apple's World is a volunteer prison, Apple sucks
