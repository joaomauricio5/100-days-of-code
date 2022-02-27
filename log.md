# 100 Days Of Code - Log

### Table of contents

| Day                 | Focus                                   | Day                 | Focus                                         |
|:-------------------:|:----------------------------------------|:-------------------:|:----------------------------------------------|
| [Day 1](#day1)      | SwiftUI - Creating and combining views  | [Day 2](#day2)      | Intro to JSON files in Swift + Enums          |
| [Day 3](#day3)      | More Enums + Prep for JSON decoding     | [Day 4](#day4)      |                                               |



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
