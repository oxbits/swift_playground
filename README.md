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

////////

// let j = 3  // ERROR: Invalid redeclaration of 'j'

////////

let size = (20, 40)
switch size {
case let (width, height) where width == height:
    println("square with sides\(width)")
    width
    height
case (1...10, 1...10):
    println("")
case let (width, height):
    println("rectangle with width \(width) and height \(height)")
    width
    height
}


////////

let frame = CGRect(x: 0, y: 0, width: 150 , height: 150)
let customView = UIView(frame: frame)  // CheckBox(frame: frame)  //  Switched to a UIView so the example would work
customView.backgroundColor = UIColor.blueColor()
customView.tintColor = UIColor.orangeColor()
//customView.isChecked = true

////////

j = 2
for var i = 0; i < 5; ++i {
    j += j * i
}
j


import XCPlayground

for (_, color) in enumerate([UIColor.orangeColor(), UIColor.greenColor()]) {
        customView.backgroundColor = color
    XCPShowView("customView", customView)
}

```

\* Swift is a proprietary language.  Apple's World is a volunteer prison.
