# 100 Days Of Code - Log

### Table of contents

| Day                 | Focus                                   | Day                 | Focus                                         |
|:-------------------:|:----------------------------------------|:-------------------:|:----------------------------------------------|
| [Day 1](#day1)      | SwiftUI - Creating and combining views  | [Day 2](#day2)      | Intro to JSON files in Swift + Enums          |
| [Day 3](#day3)      | More Enums + Prep for JSON decoding     | [Day 4](#day4)      | JSON Decoding/Encoding in Swift + Optionals   |
| [Day 5](#day5)      | Error Handling in Swift + Protocols/Generics | [Day 6](#day6) | Finally overcoming the JSON Tutorial!         |
| [Day 7](#day7)      | Closures in Swift                       | [Day 8](#day8)      | Landmarks App - MapAnnotation                 |
| [Day 9](#day9)      | Landmarks App - User Input              | [Day 10](#day8)     | Landmarks App - User Input pt.2               |
| [Day 11](#day11)    | Codewars Kata                           | [Day 12](#day12)    | Landmarks App - User Input pt.3               |
| [Day 13](#day13)    | Starting Cookcademy App                 | [Day 14](#day14)    |                                               |

--------------------------------

<a name="day1"></a>
### Day 1: 25 February 2022, Friday
### **SwiftUI - Creating and combining views**

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
1. [Landmarks - iOS App Tutorial](https://github.com/joaomauricio5/Landmarks)

--------------------------------


<a name="day2"></a>
### Day 2: 26 February 2022, Saturday
### **Intro to JSON files in Swift + Enums**

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
### **More Enums + Prep for JSON decoding**

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
### **JSON Decoding/Encoding in Swift + Optionals**

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
### **Error Handling in Swift + Protocols/Generics**

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



--------------------------------



<a name="day6"></a>
### Day 6: 2 March 2022, Wednesday
### **Finally overcoming the JSON Tutorial!**

**Today's Progress**: Today I finally completed the 2nd part of Apple's [SwiftUI Essentials Tutorial](https://developer.apple.com/tutorials/swiftui/building-lists-and-navigation). Really good to look back on [Day 2](#day2) of this challenge and remind myself that I didn't understand 80% of this part of the tutorial just 4 days ago! Splitting these problems into many different tasks or concepts to learn really has been benefitial in my progress. Also, the do-catch statement finally came in handy while I was debugging my JSON decoding implementation today. It really allowed me to find the specific part of my code that needed to be changed.  Will definitely try and use it more in the future.  
Also had the chance to learn more about Preview modifiers such as *previewLayout*, *previewDevice* and *previewDisplayName*, as well as Lists and navigation in SwiftUI Apps (using NavigationView and NavigationLink).


**Key Takeaways**:  
- In SwiftUI, you can use a Group to return multiple previews from a preview provider.
- previewLayout modifier for Previews
- previewDevice modifier can include more devices in the preview (useful to see how the app reacts to different window sizes)
- Use the previewDisplayName(_:) modifier to add the device names as labels for the previews.
- List is a container that presents rows of data arranged in a single column, optionally providing the ability to select one or more members.
- Lists work with identifiable data. You can make your data identifiable in one of two ways: by passing along with your data a key path to a property that uniquely identifies each element, or by making your data type conform to the Identifiable protocol.
- You add navigation capabilities to a list by embedding it in a NavigationView, and then nesting each row in a NavigationLink to set up a transtition to a destination view.



**Link(s) to work**
1. [Landmarks - SwiftUI App Tutorial](https://github.com/joaomauricio5/Landmarks/commits/main)


--------------------------------



<a name="day7"></a>
### Day 7: 3 March 2022, Thursday
### **Closures in Swift**

**Today's Progress**: Today I finally completed Codecademy's Course in [Intermediate Swift](https://www.codecademy.com/learn/learn-intermediate-swift) by finshing the Closures module. I should say this course stretched my brain a little bit, but it's really great to be continuously learning more and more concepts (which I can definitely apply to other programming languages apart from Swift). I have seen closures being used in some CodeWars solutions but never took the time to fully understand them. I can now see how useful they can be, specifically when paired up with Swift higher-order methods like reduce, map, filter , etc etc.


**Key Takeaways**:  
- Closures are self-contained blocks of functionality. Just like functions, closures take in arguments, execute instructions, and return a value or Void.
- Closures may be referred to as blocks or lambdas in other programming languages
- A higher-order function is a function that takes another function as an argument.
- If a function’s last argument is a closure, the function can be called using trailing closure syntax. Omit the last argument from the method call and close the parentheses. Then, define the closure immediately after the parentheses are closed.
- Shorthand argument names: argument names can be omitted in favor of $0, $1
- A closure escapes a function when it’s called after the function returns. This can happen when the closure is assigned to a variable. Escaping closures must be marked with the @escaping tag in a function signature.
- Closures can capture values from their surrounding scope. When a closure captures a value, it keeps track of it and can manipulate the value even if the original function returns.




**Link(s) to work**
1. [Closures Codecademy's Project](https://app.codingrooms.com/w/D3zvOcYMq2P8)
2. [Closures Codecademy's Cheatsheet](https://www.codecademy.com/learn/paths/learn-intermediate-swift/tracks/learn-intermediate-swift/modules/swift-closures/cheatsheet)


--------------------------------



<a name="day8"></a>
### Day 8: 4 March 2022, Friday
### **Landmarks App - MapAnnotation**

**Today's Progress**: Today I worked further on the Landmarks app - without following any tutorials, which was a nice change to really test my current SwiftUI knowledge. I worked on adding a new page where the user can have a fullscreen map which details where each Landmark is located through map pins. These map pins are clickable and take the user to the relevant LandmarkDetail page, which presents a detailed description of the Landmark. For this, I used the MapAnnotation SwiftUI view in order to place small pin Images in specific locations, which are then included in a NavigationLink taking the user to the LandmarkDetail page. Closures came in super handy and I'm glad I took the time to study them properly today. The trailing closure syntax was especially useful.  
After implementing these changes, I am sometimes getting a runtime error saying "Modifying state during view update, this will cause undefined behaviour". I read a bit on this and I am fairly understanding what the issue might be, but I plan on fixing this in the next few days after some more research.


**Key Takeaways**:  
- SF Symbols app provides a set of over 3,200 consistent, highly configurable symbols you can use in your app.
- MapMarker came in handy to quickly add markers to a map. However it proved difficult to make them clickable in order to allow navigation.
- MapAnnotation is a bit trickier to set up but it allowed me to use any icon for the map pin and then make that icon clickable to perform an action.
- I need to debug the current runtime error on the app: "Modifying state during view update, this will cause undefined behaviour"
- I want to take some time to study bindings in SwiftUI





**Link(s) to work**
1. [Landmarks App](https://github.com/joaomauricio5/Landmarks/commits/main)



--------------------------------



<a name="day9"></a>
### Day 9: 5 March 2022, Saturday
### **Landmarks App - User Input**

**Today's Progress**: Today I started the 3rd part of Apple's SwiftUI Essentials Tutorial - [Handling User Input](https://developer.apple.com/tutorials/swiftui/handling-user-input) and I managed to get through most of the project. It involved creating a way for the users to select their favorite landmarks and provide a toggle to only make their favorite landmarks visible. I now have a few extra concepts I need to learn about to continue my SwiftUI journey and be able to fully understand the tutorials: What does the *final* keyword mean before a class? What are property wrappers? When should we use @State, @Published, @EnvironmentObject and @StateObject? I will look into these concepts tomorrow and should be able to swiftly complete this section of the tutorial afterwards.

**Key Takeaways**:  
- State is a value, or a set of values, that can change over time, and that affects a view’s behavior, content, or layout. You use a property with the @State attribute to add state to a view.
- To combine static and dynamic views in a list, or to combine two or more different groups of dynamic views, use the ForEach type instead of passing your collection of data to List.
- A binding acts as a reference to a mutable state. When a user taps the toggle from off to on, and off again, the control uses the binding to update the view’s state accordingly.
- An observable object is a custom object for your data that can be bound to a view from storage in SwiftUI’s environment. SwiftUI watches for any changes to observable objects that could affect a view, and displays the correct version of the view after a change.
- I need to read more about property wrappers such as @State, @Published, @EnvironmentObject and @StateObject


**Link(s) to work**
1. [Landmarks App](https://github.com/joaomauricio5/Landmarks/commits/main)


--------------------------------



<a name="day10"></a>
### Day 10: 6 March 2022, Sunday
### **Landmarks App - User Input pt.2**

**Today's Progress**: Continued working on the 3rd part of Apple's SwiftUI Essentials Tutorial - [Handling User Input](https://developer.apple.com/tutorials/swiftui/handling-user-input). I am taking my time with these tutorials as there's often some Swift concepts I have never used before, and I want to take as much away as possible for these resources. I am struggling a little bit with Data management inside SwiftUI, specifically with all of the different property wrappers available. It's currently a bit unclear which ones to use in specific cases right, but I'll get there eventually. Today I am definitely feeling more confident with it than yestertday, as I spent quite a lot of time reading about property wrappers for storage management and examples of when/how to use them. I am expecting to feel even more confident with them in the next few days.

**Key Takeaways**:  
- Whenever an ObservableObject with a property marked @Published is changed, all views using that object will be reloaded to reflect those changes.
-  A preview fails if any subview requires a model object in the environment, but the view you are previewing doesn’t have the environmentObject(_:) modifier.
- A simple rule is this: if you see “state” in the name of a property wrapper, it means that views definitely owns the data.
- I want to make a new property owned by the current view. You should use @State for value types, and @StateObject for reference types.
I want to refer to a value created elsewhere. You should use @Binding for value types, and either @ObservedObject or @EnvironmentObject for reference types.
- [Hacking with Swift](https://www.hackingwithswift.com/quick-start/swiftui/how-to-use-environmentobject-to-share-data-between-views)
- Although class inheritance is very useful – and in fact large parts of Apple’s platforms require you to use it – sometimes you want to disallow other developers from building their own class based on yours.
Swift gives us a final keyword just for this purpose: when you declare a class as being final, no other class can inherit from it. This means they can’t override your methods in order to change your behavior – they need to use your class the way it was written.




**Link(s) to work**
1. [Landmarks App](https://github.com/joaomauricio5/Landmarks/commits/main)


--------------------------------



<a name="day11"></a>
### Day 11: 7 March 2022, Monday
### **Codewars Kata**

**Today's Progress**: Today I decided to keep it simple and spent my coding hour solving Kata in [Codewars](https://www.codewars.com/). Really nice to feel some real progress in the solutions I have been coming up with, specifically when they are super short. I reckon that longer solutions might be easier to read sometimes, however, it's good to still be able to come up with concise code. For this, some of Swift's higher-order functions such as .reduce(), .filter() have been incredibly useful. Looking forward to work with more complex Kata.

**Key Takeaways**:  
- Sometimes more concise code can be harder to read by other developers.
- Swift's higher-order functions such as .filter() and .reduce() have been really good ways to refactor Codewars' Kata solutions
- *where* is a powerful keyword within Swift to filter out values.





**Link(s) to work**
1. [Kata 1](https://www.codewars.com/kata/58cb43f4256836ed95000f97)
2. [Kata 2](https://www.codewars.com/kata/55a70521798b14d4750000a4)
3. [Kata 3](https://www.codewars.com/kata/545afd0761aa4c3055001386)
4. [Kata 4](https://www.codewars.com/kata/5715eaedb436cf5606000381)


--------------------------------



<a name="day12"></a>
### Day 12: 8 March 2022, Tuesday
### **Landmarks App - User Input pt.3**

**Today's Progress**: Data management in SwiftUI is getting clearer now. [Hacking with Swift](https://www.hackingwithswift.com/) has been such an amazing resource and I have been using it quite a lot to get to understand the scenarios where we would use @EnvironmentObject, @Published, @StateObject, etc etc. I finally finsihed the 3rd part of Apple's SwiftUI Essentials Tutorial - [Handling User Input](https://developer.apple.com/tutorials/swiftui/handling-user-input). Looking back over the whole project, the way data flows from view to view is starting to make a bit more sense, specifically when different views share the same model data. I am really curious to start learning more about the MVVVM design. 

**Key Takeaways**:  
- Static variables are those variables whose values are shared among all the instance or object of a class. When we define any variable as static, it gets attached to a class rather than an object.
- The title string that you provide for the button’s label doesn’t appear in the UI when you use the iconOnly label style, but VoiceOver uses it to improve accessibility.
- [Hacking with Swift - SwiftUI Tips and Tricks](https://www.hackingwithswift.com/quick-start/swiftui/swiftui-tips-and-tricks)
- [Where keyword](https://www.avanderlee.com/swift/where-using-swift/)





**Link(s) to work**
1. [Landmarks App](https://github.com/joaomauricio5/Landmarks/commits/main)


--------------------------------



<a name="day13"></a>
### Day 13: 9 March 2022, Wednesday
### **Starting Cookcademy App**

**Today's Progress**: Today I decided to put Landmarks on the side for a bit (next tutorial step in that app will be to [learn to draw and animate with SwiftUI](https://developer.apple.com/tutorials/swiftui/drawing-paths-and-shapes)), and continue my progress in Codecademy's [iOS Developer Career Path](https://www.codecademy.com/learn/paths/ios-developer) by starting the foundation for the Cookcademy app. This is a digital recipe book where users can view, create, edit, favorite, and save recipes.  
Today was all about creating the model for the application, specifically around setting up the Recipe structure. Learned a few new things which are detailed in the Key Takeaways below.

**Key Takeaways**:  
- Use MVVM as a way of getting some of our program state and logic out of our view structs. We are, in effect, separating logic from layout.
- Both the static and class keywords allow us to attach variables to a class rather than to instances of a class. 
Where static and class differ is how they support inheritance: When you make a static property it becomes owned by the class and cannot be changed by subclasses, whereas when you use class it may be overridden if needed.
- With Data, we can ask iOS to ensure the file is written with encryption so that it can only be read once the user has unlocked their device. This is in addition to requesting atomic writes – iOS does almost all the work for us.
- The String(format:) method is used to create a formatted String from a Double. The %g String Format Specifier specifier suppresses any trailing zeros. If you had "1.10000", it would turn your number to "1.1". This functionality allows you to guarantee that the numbers are printed in a readable way.






**Link(s) to work**
1. [Cookcademy App](https://github.com/joaomauricio5/Cookcademy/commits/main)
