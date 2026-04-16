# Advanced Python Programming Course
This holds PDF's and lecture slides for an advance python programming course.

## The why?
Most college courses use Python as the starting language to teach problem solving and programming concepts. The same goes for MCC(Omaha). So by the end of that introductory course most books are 75% give or take covered. So what do we cover in the next course? Finish out that book and then come up with something else? That is what I have done here except I used ChatGPT to help me generate a free OER book that not only review Python but then goes into deeper software development concepts.

## Course/Book Layout
Our college has 10/11 week quarters. This course is laid out into 9 modules (with the 8th chapter being two modules on databases). Then the final 1-2 weeks is taking what they have built and adding to it for the final project. This usually involves creating a whole new object, adding it into the console based system, exporting out as needed with files and CRUD operations to the database.

### Chapter 1 - Python Review
* Most students learned Python with an introductory course but do they fully understand the full operation. This chapter reviews these and also focuses on building console based application and keeping the console app running through a menu system, functionality separated into functions, and holding data through lists and dictionaries. We give the student a starter app file that they then add to their git repository and apply the required modifications. Most students my not have seen a good IDE so we implement using PyCharm and also show some debug features. Throughout future lecture videos when problems occur I continue to put break points to step through

### Chapter 2 - Functions, Modules and Exceptions
* In this chapter we look at functions more in depth. We also introduce type hints in python by applying those to function parameters and also return types. This is helpful when students have to move on to another language for our degree. Then we discuss separation of concerns with Modules and how we can use Python Packages to organize our files. We look at putting our data handling(temporary local database as a list) in one file, our UI in another and some exception handling helper functions(for constant number inputs and date/time handling) in another module. We also explore built in modules in Python that are useful like os, datetime, etc. Exception handling may have been discussed in the previous class but we really hit it hard to handle all exceptions so that our programs don't crash

### Chapter 3 - Object Oriented Programming
* Depending on the introductory class some students may have gotten an introduction to creating their own or just using them. Here we deep dive into objects. Discuss how python does objects vs other languages but still apply basic concepts of needing a constructor, getter/setters and then using specialty methods (dunder).

### Chapter 4 - Inheritance, Polymorphism, and Enums
* We further explore OOP with implementing inheritance. The previous week's assignment would have at least two objects that share similar attributes so we show how we can combine those and make a base class then sub class that inherit those. We also discuss polymorphism to use both these sub classes and other objects. Lastly Python uses inheritance to implement enums so we can introduce that here.

### Chapter 5 - Unit Testing
* Now that we have our objects created we can make sure they work as intended so let's introduce unit testing. We explore the use of the unittesting library in python to test our objects, the mock for faking our console input and any other functions/methods that we need to test.

### Chapter 6 - Data Structures and Comprehensions
* We have already litely discussed lists and dictionaries in our review and also the introductory classes but do students really understand them? Here we further discuss all the methods and functions we can use with lists and dictionaries. We also discuss the use of sets and tuples. Lastly we explor more with actually using data structures by implementing modify and delete operations to our objects that are stored in lists in our console application for the assignment. This chapter I also use AI to generate a data loading function by giving it my objects code and dictionary/list database (the fake temp database as a list made in chapter 2) so that we can better test our data structures modify and delete operations. Students also perform a filter operation using set comprehensions.

### Chapter 7 - File Parsing
* Up until this point our data isn't saved. When we run to test our application it is all manually. So a lot of repeated work. With this chapter we explore the use of CSV, XML and JSON files. Python has those built in libraries to handle them. We leverage these libraries and read/write to these different file types. For the assignment I make student save out the filtered data from chapter 6 to a CSV file as a report. Then I make them read in an XML file as a sort of "migration" from old system to new. Lastly we use JSON data to read/write the main information of our application.

### Chapter 8 - Databases in Python
* Now we introduce databases and how we use them with Python. We focus on using SQLite databases and hardcoding the SQL CRUD operations. In future courses we talk about ORMs. For my course I have this chapter split up between two weeks/modules. First week/module we do Insert and Select. The second week we do Update and Delete.

## Work In Progress
I created this book on the fly. I did some modifications and restructuring from what ChatGPT outputed for me. I still have not fully "reviewed" for all grammatical error and rewrites.

