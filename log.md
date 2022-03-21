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
| [Day 13](#day13)    | Starting Cookcademy App                 | [Day 14](#day14)    | Cookcademy App - Adding a list and sections   |
| [Day 15](#day15)    | SwiftUI Grids                           | [Day 16](#day16)    | Codewars Kata                                 |
| [Day 17](#day17)    | Cookcademy Category Grid + Codewars     | [Day 18](#day18)    | HackerRank + Codewars                         |
| [Day 19](#day19)    | More HackerRank                         | [Day 20](#day20)    | More HackerRank pt.2                          |
| [Day 21](#day21)    | Toolbars and Sheets in SwiftUI          | [Day 22](#day22)    | Adding recipes to Cookcademy + Sheets/Toolbars|
| [Day 23](#day23)    | Reviewing Closures + HackerRank         | [Day 24](#day24)    | Forms, TextEditors and Pickers in SwiftUI     |
| [Day 25](#day25)    | HackerRank's Basic Problem Solving Certificate | [Day 26](#day26)    |                                               |

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

**Today's Progress**: Today I finally completed Codecademy's Course in [Intermediate Swift](https://www.codecademy.com/learn/learn-intermediate-swift) by finishing the Closures module. I should say this course stretched my brain a little bit, but it's really great to be continuously learning more and more concepts (which I can definitely apply to other programming languages apart from Swift). I have seen closures being used in some CodeWars solutions but never took the time to fully understand them. I can now see how useful they can be, specifically when paired up with Swift higher-order methods like reduce, map, filter , etc etc.


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


--------------------------------



<a name="day14"></a>
### Day 14: 10 March 2022, Thursday
### **Cookcademy App - Adding a list and sections**

**Today's Progress**: Today I continued working on the Cookcademy app - so far it's been very similar to the Landmarks project in the sense that it presents the user with a List with clickable items that redirect the user to a detailView. Hoping that it gets a bit more complex in the next few steps, but it's good to get some extra practice with Lists and the MVVM software architectural pattern - specifically the implementation of property wrappers like @Published, @StateObject and @EnvironmentObject. I was also introduced to the concept of Sections, to organize a list. 

**Key Takeaways**:  
- Creating a list requires either passing in Identifiable structures or specifying an id with a keypath.
- Swift keypaths are a means to store a reference to a property, without actually storing the value of the property itself. Think of it as a path to the property.
- The UUID structure “creates a universally unique value that can be used to identify types, interfaces, and other items”. 
- When a structure conforms to the Identifiable protocol, it means that it must have a property called id that is a unique identifier. By using an instance of the UUID structure (built into Swift Foundation) we guarantee that id is unique. 
- If you remove the NavigationView, you will no longer be able to see the navigation title in the preview. 



**Link(s) to work**
1. [Cookcademy App](https://github.com/joaomauricio5/Cookcademy/commits/main)



--------------------------------



<a name="day15"></a>
### Day 15: 11 March 2022, Friday
### **SwiftUI Grids**

**Today's Progress**: Today I studied and practiced Grids in SwiftUI. The implementation seems to be very simple, and it's really seamless to adapt the grids to different device sizes. I created a simple scrollable calendar which uses Capsules for each day of the week. Each day is then laid out (7 days horizontally) into the standard calendar layout we know. I started to import this knowledge into the Cookcademy app, to define a grid with NavigationLinks that take the user to different categories of recipes (breakfast, lunch, dinner, dessert).

**Key Takeaways**:  
- In order to create our grid-based view, we’ll need to define an array of GridItem instances first. These GridItem instances serve to describe the layout properties of the grid. We can use various types of GridItem instances to get the spacing and alignment of the columns or rows of the grid exactly how we wish. We can even use them to describe a grid that adjusts dynamically based on the size and orientation of the device.
- Similar to the concept of lazy properties, the Lazy in LazyVGrid and LazyHGrid refers to the fact that the elements of the grid aren’t created until they are needed to display in the view.
- Loading thousands of images would cause the app to slow down. By using lazy loading, we create much smoother, more performant user experiences.
- With GridItem, the flexible option creates a column that takes up the available width it has. You must define a minimum width, and you can optionally specify a maximum width.
- Another useful feature of grids is the ability to pin views while scrolling. The section header view sticks to the top of the screen while you are scrolling through that particular section. This can help create a smooth, intuitive user experience.
- You are not supposed to do any kind of looping/condition making block of codes while creating Array's or Dictionary.


**Link(s) to work**
1. [Cookcademy App](https://github.com/joaomauricio5/Cookcademy/commits/main)


--------------------------------



<a name="day16"></a>
### Day 16: 12 March 2022, Saturday
### **Codewars Kata**

**Today's Progress**: Today I had to keep it short so I completed a few Codewars' Kata for an hour. I'm starting to feel more confident with a bit more complex coding challenges. I managed to complete a level 6 Kata and it definitely feels good. Looking forward to being able to complete level 1 challenges but, in the meanwhile, I'm really enjoying the process of getting there. Will continue working on the Cookcademy app in the next few days.

**Key Takeaways**:  
- Completed my first 6 kyu Codewars' Kata!
- Got some more practice with the *filter* higher-order function. Definitely proving to be super useful for these challenges.



**Link(s) to work**
1. [Kata 1](https://www.codewars.com/kata/5813d19765d81c592200001a)
2. [Kata 2](https://www.codewars.com/kata/5d5ee4c35162d9001af7d699)
3. [Kata 3](https://www.codewars.com/kata/5596f6e9529e9ab6fb000014)




--------------------------------



<a name="day17"></a>
### Day 17: 13 March 2022, Sunday
### **Cookcademy Category Grid + Codewars**

**Today's Progress**: Today I managed to complete another section in Codecademy's [iOS Developer Career Path](https://www.codecademy.com/learn/paths/ios-developer) by building a category grid for the Cookcademy app. This meant creating a grid of 4 categories for the recipes (breakfast, lunch, dinner and dessert), and redirecting the user to the chosen list of recipes, while still keeping the MVVM model by making sure the views don't directly interact with the models. I'm finding that trying to implement the requirements myself rather than directly following the tutorials has been really beneficial. I then use the tutorials to get a few hints or to compare with my solution. I also managed to complete 7 Codewars Kata. I'm really enjoying the challenges.

**Key Takeaways**:  
- For the iOS project tutorials, I'm going to try to implement the app requirements mostly by myself rather than just following the tutorial steps.
- I am now getting comfortable with Level 8 and 7 Kata in Codewars, so I'm going to try to challenge myself a bit more with Level 6 challenges.
- The map() method allows us to transform arrays (and indeed any kind of collection) using a transformation closure we specify. The return value will be an array of the same size, containing your transformed elements.
- The Image is modified to be .resizeable, forcing the image to fill all available space. Then, the image’s aspect ratio is set to .fit which forces the content to fit within the ZStack‘s frame. Here, the image will continue to shrink until the width of the photo matches the width of the view.


**Link(s) to work**
1. [Kata 1](https://www.codewars.com/kata/5544c7a5cb454edb3c000047)
2. [Kata 2](https://www.codewars.com/kata/57a0e5c372292dd76d000d7e)
3. [Kata 3](https://www.codewars.com/kata/5545f109004975ea66000086)
4. [Kata 4](https://www.codewars.com/kata/5583090cbe83f4fd8c000051)
5. [Kata 5](https://www.codewars.com/kata/5168bb5dfe9a00b126000018)
6. [Kata 6](https://www.codewars.com/kata/57eae65a4321032ce000002d)
7. [Kata 7](https://www.codewars.com/kata/5467e4d82edf8bbf40000155)
8. [Cookcademy App](https://github.com/joaomauricio5/Cookcademy/commits/main)


--------------------------------



<a name="day18"></a>
### Day 18: 14 March 2022, Monday
### **HackerRank + Codewars**

**Today's Progress**: Today I focused solely on coding challenges. I started using [HackerRank](https://www.hackerrank.com/dashboard) as it was recommended for technical interview prepping. The challenges I've completed today were quite simple, but I'm pushing myself to also think out loud and explain my process as if someone else was seeing me code. From what I've read, being able to explain my thought process is super important for technical interviews and it definitely makes it a little bit harder for me at the moment, so I want to make sure I practice as much as possible.

**Key Takeaways**:  
- I'm going to start using [HackerRank](https://www.hackerrank.com/dashboard) more frequently to prep for technical interviews.
- I'm going to focus on also explaining my thought process while I'm solving coding challenges.
- I'm thinking of also completing HackerRank's 30 Days of Code by solving at least one of their suggested challenges each day.


**Link(s) to work**
1. [HackerRank 1st challenge](https://www.hackerrank.com/challenges/one-month-preparation-kit-plus-minus/problem?h_r=profile)
2. [HackerRank 2nd challenge](https://www.hackerrank.com/challenges/one-month-preparation-kit-mini-max-sum/problem)
3. [Codewars Kata](https://www.codewars.com/kata/5667e8f4e3f572a8f2000039)





--------------------------------



<a name="day19"></a>
### Day 19: 15 March 2022, Tuesday
### **More HackerRank**

**Today's Progress**: Today was quite a busy day travelling but I still put in some practice with HackerRank challenges and Codecademy practice sessions for the [iOS Developer Career Path](https://www.codecademy.com/learn/paths/ios-developer). I've recently applied for 2 roles that might lead to a technical interview so I'm starting to feel like I should shift my focus onto these kinds of challenges, at least for me to feel a bit more prepared. I'm going back to SwiftUI in a few days.
I also realised how useful the if let or guard let statements are when dealing with optionals. A few weeks ago I was struggling with a few exercises with Dictionaries because I was dealing with keys that hadn't been yet initialised. In these cases, we can use the guard let / if let statements to check if the key-value pair is already initialized -> if it is, then we proceed with our code, otherwise we can initialise them. Really useful when trying to figure out the number of times that a specific string or int shows up in an array, for example.


**Key Takeaways**:  
- Internal is the default level of access control in Swift when creating variables
- Use guard let or if let when trying to access dictionary keys that may not have been initialized already



**Link(s) to work**
1. [HackerRank 1st challenge](https://www.hackerrank.com/challenges/30-data-types?h_r=profile)
2. [HackerRank 2nd challenge](https://www.hackerrank.com/challenges/one-month-preparation-kit-lonely-integer?h_r=profile)
3. [iOS Developer Career Path](https://www.codecademy.com/learn/paths/ios-developer)





--------------------------------



<a name="day20"></a>
### Day 20: 16 March 2022, Wednesday
### **More HackerRank pt.2**

**Today's Progress**: Today I continued working on HackerRank's coding challenges. I've started doing their 30 Days of Code which I'm also expecting to complete, but those challenges are still fairly easy at the moment. Today I've also changed my approach to these problems - although I can normally come up with quick solutions using Swift's built-in functions, I'm pushing myself to also provide solutions that don't use functions like map, filter, reduce, etc, just in case I'm asked to do that in a technical interview. So, for each coding challenge, I try to provide 1 lenghtier solution with no major Swift functions and another shorter one that uses Swift's "shortcuts". So, rather than focusing on the number of challenges completed, I'm trying to explore different solutions as much as I can, even if I can come up with one solution very quickly.


**Key Takeaways**:  
- When working with coding challenges, it seems to be good practice to also find solutions that don't rely on specific Swift functions (like map, filter, reduce etc).
- I'm getting more practice with explaining my solutions out loud and also my thought process while I'm completing coding challenges.



**Link(s) to work**
1. [HackerRank 1st challenge](https://www.hackerrank.com/challenges/one-month-preparation-kit-sparse-arrays/problem)
2. [HackerRank 2nd challenge](https://www.hackerrank.com/challenges/30-operators/problem?h_r=profile)
3. [HackerRank 3rd challenge](https://www.hackerrank.com/challenges/one-month-preparation-kit-the-birthday-bar/problem)


--------------------------------



<a name="day21"></a>
### Day 21: 17 March 2022, Thursday
### **Toolbars and Sheets in SwiftUI**

**Today's Progress**: Today I continued my learning in Codecademy's [iOS Developer Career Path](https://www.codecademy.com/learn/paths/ios-developer) by practicing with Sheets and Toolbars in SwiftUI. I took a quiz and created a small project to implement what I've learnt but tomorrow I'll be working on adding these to the Cookcademy app. Additionally, I've also completed 2 HackerRank challenges. They are starting to get a bit more complex but I'm really happy I've been able to handle the challenges by breaking them down into a few different steps.


**Key Takeaways**:  
- SwiftUI’s toolbar modifier allows for placement of views along the top or bottom space of a view. For a toolbar to work properly, it must be embedded in a NavigationView.
- According to the Apple docs, a toolbar wraps views just like a VStack or NavigationView
- the toolbar is by default a transparent container.
- A ToolbarItem can be given a specific placement onto the toolbar. The placement is determined by the optional placement parameter for ToolbarItem which takes in a value of type ToolbarItemPlacement. If there is no placement given, it will default to the top right corner.
- SwiftUI sheets are used to present a new view over an existing one. Think of this as a stack of papers. You can have multiple sheets on top of one another, and the middle one can be accessed by removing the ones above it.


**Link(s) to work**
1. [HackerRank 1st challenge](https://www.hackerrank.com/challenges/one-month-preparation-kit-the-birthday-bar/problem?h_r=profile)
2. [HackerRank 2nd challenge](https://www.hackerrank.com/challenges/30-conditional-statements/problem?h_r=profile)
3. [iOS Developer Career Path](https://www.codecademy.com/learn/paths/ios-developer)



--------------------------------



<a name="day22"></a>
### Day 22: 18 March 2022, Friday
### **Adding recipes to Cookcademy + Sheets/Toolbars**

**Today's Progress**: Today I continued working on the Cookcademy app by adding a Modal View that provides the foundation for users to add recipes to the app. Currently it only populates a newRecipe with test strings, but in the next few days it will allow users to fully save whole recipes with their own text input. I also got some practice with the @Binding property wrapper in order to understand which cases it should be used in.  
While learning what a modal view was, I also explored Apple's [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/ios/overview/themes/), and it seems like such a great resource for making applications, as it provides tips to create great user experiences.  
Additionally, I also completed 4 [HackerRank](https://www.hackerrank.com/dashboard) challenges.


**Key Takeaways**: 
- According to the [Apple Docs](https://developer.apple.com/design/human-interface-guidelines/ios/app-architecture/modality/), a modal view is a temporary view that’s separate from the user’s previous current context and requires an explicit action to exit.
- Presenting content modally can: help people focus on a self-contained task or set of closely related options; ensure that people receive critical information and, if necessary, act on it.
- @Binding lets us declare that one value actually comes from elsewhere, and should be shared in both places. This is not the same as @ObservedObject or @EnvironmentObject, both of which are designed for reference types to be shared across potentially many views.
- The binding allows ModifyRecipeView to access and modify the original property as if it owned recipe (*Recipe()*).


**Link(s) to work**
1. [HackerRank - Diagonal Difference](https://www.hackerrank.com/challenges/one-month-preparation-kit-diagonal-difference?h_r=profile)
2. [HackerRank - Permuting Two Arrays](https://www.hackerrank.com/challenges/one-month-preparation-kit-two-arrays?h_r=profile)
3. [HackerRank - Pangrams](https://www.hackerrank.com/challenges/one-month-preparation-kit-pangrams?h_r=profile)
4. [HackerRank - XOR Strings 2](https://www.hackerrank.com/challenges/one-month-preparation-kit-strings-xor?h_r=profile)
6. [Cookcademy App](https://github.com/joaomauricio5/Cookcademy/commits/main)


--------------------------------



<a name="day23"></a>
### Day 23: 19 March 2022, Saturday
### **Reviewing Closures + HackerRank**

**Today's Progress**: Today I came back from work quite late so I ended doing just a quick review on closures through Codecademy's [iOS Developer Career Path](https://www.codecademy.com/learn/paths/ios-developer) and a few HackerRank challenges. I managed to finish 2 challenges but I also started a third one which I still need some time with.   
I noticed that HackerRank also offers Problem Solving Certificates, so I'm going to take the exam for the Basic certificate in the next few days to test how my skills evolved in these past few weeks.


**Key Takeaways**: 
- [HackerRank Certifications](https://www.hackerrank.com/skills-verification)


**Link(s) to work**
1. [HackerRank - Time Conversion](https://www.hackerrank.com/challenges/one-month-preparation-kit-time-conversion/problem?h_r=profile)
2. [HackerRank - Counting Sort](https://www.hackerrank.com/challenges/one-month-preparation-kit-countingsort1?h_r=profile)





--------------------------------



<a name="day24"></a>
### Day 24: 20 March 2022, Sunday
### **Forms, TextEditors and Pickers in SwiftUI**

**Today's Progress**: Today I continued Codecademy's [iOS Developer Career Path](https://www.codecademy.com/learn/paths/ios-developer) and learnt about some new SwiftUI concepts, such as Form, TextField, TextEditor and Picker. With this, I created a small app which consists of a simple contact form that utilises these new concepts. The apps I've been working on so far only consisted of buttons, text, navigation, haven't included any data editing, so I was looking forward to concepts I've learnt today. I'm liking SwiftUI more and more each day. Very intuitive so far and straight to the point.  
I've also completed a small quiz about today's lessons and the daily challenge from HackerRank's 30 Days of Code.


**Key Takeaways**: 
- The Form element wraps controls used for data entry. SwiftUI includes many of those controls, including toggles, text fields, pickers, and more.
- A TextField is a view that lets us enter and edit short bits of text
- While TextField is great for short bits of text, we’ll want to use something different for long-form text: the TextEditor view. Text editors let us display and edit as many lines of text as we need—perfect for composing messages, descriptions, and anything else that won’t fit on one line.
- Just as we’ve learned to do with lists, we can organize our forms using sections.
- By default, pickers use a NavigationLink to present a list of options on a separate page.
- Notice that each option has a tag attached. That’s how SwiftUI knows what value the picker represents.
- SwiftUI lets us choose from a few different picker styles that might better suit our needs. We can apply a picker style using the .pickerStyle() view modifier. 


**Link(s) to work**
1. [Cookcademy App](https://github.com/joaomauricio5/Cookcademy/commits/main)




--------------------------------



<a name="day25"></a>
### Day 25: 21 March 2022, Monday
### **HackerRank's Basic Problem Solving Certificate**

**Today's Progress**: Today I was 100% focused on HackerRank's coding challenges. I felt prepared for the [Basic Problem Solving Certificate](https://www.hackerrank.com/skills-verification/problem_solving_basic) so I decided to give it a try. It was a 1h30 test with 2 different challenges. I was quite impressed that, even though I got to the solutions and my test cases were passing, the submission wasn't being counted as "valid" or "correct" because the computation for my algorithm took longer than HackerRank's limit for Swift (2 seconds). Although this was frustrating, as the problem solving part of it was "correct", it served as a "wake up call" for me to start studying the time complexity of my solutions and how to make them more efficient. I'll be able to take the test again in 30 days.


**Key Takeaways**: 
- HackerRank Certificates apparently require the solutions for their challenges to be able to be computed quicker than their specified maximum time for the used language.
- I need to start thinking about the time complexity of my solutions to coding challenges. How can I start studying it?


**Link(s) to work**
1. [HackerRank - Flipping bits](https://www.hackerrank.com/challenges/one-month-preparation-kit-flipping-bits?h_r=profile)
2. [HackerRank - Sales by Match](https://www.hackerrank.com/challenges/one-month-preparation-kit-sock-merchant?h_r=profile)
3. [HackerRank - Zig Zag Sequence](https://www.hackerrank.com/challenges/one-month-preparation-kit-zig-zag-sequence?h_r=profile)
4. [HackerRank - Drawing Book](https://www.hackerrank.com/challenges/one-month-preparation-kit-drawing-book?h_r=profile)
5. [HackerRank Basic Problem Solving Certificate](https://www.hackerrank.com/skills-verification/problem_solving_basic)
