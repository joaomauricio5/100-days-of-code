# 100 Days Of Code - Log

### Table of contents

| Day                 | Focus                                   | Day                 | Focus                                         |
|:-------------------:|:----------------------------------------|:-------------------:|:----------------------------------------------|
| [Day 1](#day1)      | SwiftUI - Creating and combining views  | [Day 2](#day2)      | Intro to JSON files in Swift + Enums          |
| [Day 3](#day3)      | More Enums + Prep for JSON decoding     | [Day 4](#day4)      | JSON Decoding/Encoding in Swift + Optionals   |
| [Day 5](#day5)      | Error Handling in Swift + Protocols/Generics | [Day 6](#day6) |                                               |

--------------------------------

<a name="day1"></a>
### Day 1: 25 February 2022, Friday

**Today's Progress**: Finally, the first day of the 100DaysOfCode. I'm pretty excited to push myself to stay consistent (which is something I'm struggling with at the moment), and I want to use this challenge to really progress my knowledge of iOS Development while building some interesting apps. I have been using Swift for a while now, but I feel like I should really focus on SwiftUI.  
Today I finished Part 1 of Apple's [Introducing SwiftUI Tutorial](https://developer.apple.com/tutorials/swiftui/creating-and-combining-views). I'm actually impressed with how simple it was to create a fairly good-looking UI and it got me super curious for the next few parts of the course.  
Apart from the tutorial tasks, I managed to add a MapMarker to the map view - this was a lot more complex than I was expecting as the process to do it is not super straighforward. 
I also learned about a few useful Xcode features like the SwiftUI inspector and the Views/Modifiers library.   

**Key Takeaways**: 

- [gitignore.io](https://www.toptal.com/developers/gitignore) was super useful to create the .gitignore file for the project I worked on today.
- Managed to get some more practice with Git and Github.
- Learned about the SwiftUI inspector in Xcode 
- The Views and Modifiers library in Xcode will definitely come in handy.
- First time using MapKit
- We can use the @State attribute to establish a source of truth for data in our app that we can modify from more than one view.

**Link(s) to work**
1. [Landmark - iOS App Tutorial](https://github.com/joaomauricio5/Landmarks)

--------------------------------


<a name="day2"></a>
### Day 2: 26 February 2022, Saturday

**Today's Progress**: Today I started the 2nd part of Apple's [Introducing SwiftUI Tutorial](https://developer.apple.com/tutorials/swiftui/building-lists-and-navigation) (Building Lists and Navigation) and made some progress, but ultimately got stuck for a while, specifically in the part where we need to extract data from a JSON file and assign it to an object. Although we have access to the code that does exactly that, I'm not yet 100% understanding it, and I have the feeling that understanding this is going to be really useful. However, today I'm pretty tired from work (arrived home at 9PM) so I put JSON on hold until tomorrow and I worked on something a little bit simpler.  
I finished the Enums section of Codecademy's [iOS Developer Career Path](https://www.codecademy.com/learn/paths/ios-developer), which allowed me code a little bit with iterating over enums, extracting and assigning rawValues, associated values, as well as defining/using methods and computed properties within enums.

**Key Takeaways**: 

- JSON is an open standard file format and data interchange format that uses human-readable text to store and transmit data objects consisting of attribute–value pairs and arrays.
- Planned in some questions to explore tomorrow around extracting data from JSON files specifically with Swift
- Got some more practice with computed properties, which I wasn't 100% comfortable with
- Enumerations (or enums) are used to define a new custom type with a list of possible cases. When creating an instance of an enumeration, its value must be one of the cases.
- [Enums cheatsheet](https://www.codecademy.com/learn/paths/ios-developer/tracks/exploring-recipes-swiftui/modules/swift-enumerations/cheatsheet)

**Link(s) to work**
1. [Landmark - iOS App Tutorial](https://github.com/joaomauricio5/Landmarks)
2. [Enums in Codecademy's iOS Developer Career Path](https://www.codecademy.com/paths/ios-developer/tracks/exploring-recipes-swiftui/modules/swift-enumerations/projects/numero-uno-software-store)

--------------------------------


<a name="day3"></a>
### Day 3: 27 February 2022, Sunday

**Today's Progress**: Today I completed Codecademy's Enums project for Swift. Not really complex but forced me to practice and actually utilise what I learnt yesterday about Enums in a more "real-world" scenario. 
Additionally, I went back to the part where I got stuck in yesterday's [SwiftUI - Building Lists and Navigation](https://developer.apple.com/tutorials/swiftui/building-lists-and-navigation) (Decoding JSON files) and identified what I need to learn to overcome this part: Tomorrow I will go through Codecademy's JSON Encoding and Decoding article in Swift, [Swift's Error Handling](https://docs.swift.org/swift-book/LanguageGuide/ErrorHandling.html) (specifically do-catch statements and the *try* keyword), as well as studying/practicing generics and guard statements. Realistically, these are the concepts I don't fully understand from going through Apple's SwiftUI tutorial source code, so I'm expecting that splitting it into these many parts will help me progress.

**Key Takeaways**:  
  
Checklist for tomorrow to understand the JSON file decoding part of [SwiftUI - Building Lists and Navigation](https://developer.apple.com/tutorials/swiftui/building-lists-and-navigation):
- Codecademy - JSON Encoding and Decoding in Swift
- Generics
- Guard statements
- Error handling in Swift (do-catch statements and *try* keyword)



**Link(s) to work**
1. [Enums Codecademy's Project](https://app.codingrooms.com/w/fAxyqpXjzL5F)

--------------------------------
<a name="day4"></a>
### Day 4: 28 February 2022, Monday

**Today's Progress**: Today I went through Codecademy's article about JSON Decoding and Encoding in Swift and realised that, actually, the process itself is fairly simple, as long as we are working with structures that only have properties that conform to Encodable/Decodable/Codable. This made me acknowledge that what I wasn't really understanding in the JSON file decoding part of [SwiftUI - Building Lists and Navigation](https://developer.apple.com/tutorials/swiftui/building-lists-and-navigation) was actually not the JSON handling itself, but other intermediate Swift concepts that I never used myself: Optionals, Generics, do-catch statements, the *try* keyword and throwing functions.   
With this in mind, I completed the Codecademy module about Swift Optionals, which forced me to utilise the ***!*** operator to force unwrap optionals, optional binding with the *if let* statement, *guard* statements, and the *?? - nil-coalescing* operator. I finished the day of by completing a small Codecademy project using what I learnt about Optionals (link is below)

**Key Takeaways**:  
  
- JavaScript Object Notation, abbreviated as JSON, is a format for storing data. When online APIs send data to an application, they usually use JSON as the format for the data. Competing formats to JSON include XML and YAML.
- JSON objects are very similar to Swift dictionaries. Just like a dictionary, a JSON object contains some number of key-value pairs.
- *Codable* protocol combines the *Encodable* and *Decodable* protocols
- Swift's Foundation framework includes JSONEncoder and JSONDecoder
- Optionals represent variables that might be absent
- Force unwrapping - ! Only use the ! operator if you are absolutely sure that the value isn’t nil. Otherwise, the program will crash.
- Safely unwrap optionals by using an if let statement to bind the optional to a new variable.
- The nil-coalescing operator ?? unwraps an optional value and provides a default if the optional is nil.
- A guard block is another way to write a conditional in Swift. All guard statements must have an else block that exits the current scope if the boolean expression is false. If the guard statement is true, the code below continues executing.



**Link(s) to work**
1. [Optionals Codecademy's Project](https://app.codingrooms.com/w/EsNzkXZuZ9Oz)
2. [Optionals Cheatsheet](https://www.codecademy.com/learn/paths/ios-developer/tracks/editing-and-favorting-recipes-swiftui/modules/swift-optionals-module/cheatsheet)



--------------------------------



<a name="day5"></a>
### Day 5: 1 March 2022, Tuesday

**Today's Progress**: Today I started by learning Error Handling with Swift. I explored what throwing functions are and how they can be useful in order to specify the kinds of errors our programs might come across. To call throwing functions I also learned about the *try* keyword, its different variations (*try*, *try?* and *try!*), and the do-catch statement. Lastly, I completed a module from Codecademy's [Learn Intermediate Swift Course](https://www.codecademy.com/learn/learn-intermediate-swift) regarding Protocols and Generics, which culminated in a small project exploring those concepts (link [here](https://app.codingrooms.com/w/ILhbd3gbqTAe)).  
With this new knowledge, I now feel ready to continue the [SwiftUI - Building Lists and Navigation](https://developer.apple.com/tutorials/swiftui/building-lists-and-navigation) Tutorial in such a way that I actually understand what is going on. I will continue that project tomorrow!

**Key Takeaways**:  
- Throwing functions are those that will flag up errors if problems happen, and Swift requires you to handle those errors in your code.
- You need to use the try keyword to call a throwing function.
- Using try! is like force unwrapping an optional, and should be used only when you are sure that no errors will be thrown. Use try! whenever you want to crash when a error is thrown
- If you’d like to call a throwing function safely but don’t need to handle the errors independently, you can use try?. Using try? means that if the call fails, it simply becomes nil. Using try? converts the throwing function’s return type into an optional.
- You use a do-catch statement to handle errors by running a block of code. If an error is thrown by the code in the do clause, it’s matched against the catch clauses to determine which one of them can handle the error.
- A protocol is a set of standards that classes, structs, or enums can choose to implement in their own ways. These standards come in the form of properties and functions.
- The definitions of protocols are very similar to classes and structs. However, in the case of protocols, the definition does not implement the properties and functions. Instead, the class or struct that adopts the protocol handles the implementation of the properties and methods.
- A protocol can inherit from another protocol, like a class can inherit from another class.
- In an extension for a protocol, you can provide default implementations of its requirements.
- Generics allow us to create functions that make few assumptions about the underlying data types of its arguments and can be used with multiple data types.
- Opaque types allow us to hide the specific data type that is being returned from the caller. The caller doesn’t need to know the exact type being returned in this case, only that the function should return something that conforms to a certain protocol.





**Link(s) to work**
1. [Protocols/Generics Codecademy's Project](https://app.codingrooms.com/w/ILhbd3gbqTAe)
