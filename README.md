<h1>Kitchen Companion - Final Design Report</h1>
Table of Contents:

- [Project Description](#project-description)
- [User Interface Specification](#user-interface-specification)
- [Test Plan and Results](#test-plan-and-results)
- [User Manual](#user-manual)
- [Spring Presentation](#spring-presentation)
- [Expo Poster](#expo-poster)
- [Assessments](#assessments)
  - [Fall Assessment](#fall-assessment)
  - [Spring Assessment](#spring-assessment)
- [Summary of Hours](#summary-of-hours)

# Project Description
Choosing recipes to cook, specifically during a busy work week, can be hard and tiresome. Even if you have an idea of what you want to eat, you might find out that you are missing a key ingredient, making the process of choosing what to cook even more frustrating. 
Kitchen Companion is a mobile application that helps alleviate any stress when it comes to figuring out what to cook. It will allow users to keep track of what ingredients they have available and give them recipes to cook based on what they have. 
By using kitchen companion, users will spend less time trying to figure out what they can cook, and more time eating delicious meals.

Kitchen Companion is an Android application that allows users to keep track of what ingredients they have in their kitchen, save recipes to a recipe book, and get recipes from their recipe book based on the ingredients they have in their kitchen. This project aims to get more people into cooking at home by helping alleviate any stress that comes with deciding what to cook.

# User Interface Specification

<img src="files/ui_main.jpg" alt="Main Screen" width="200"/>  <img src="files/ui_recipes.jpg" alt="Recipes Screen" width="200"/>  <img src="files/ui_ingredients.jpg" alt="Ingredients Screen" width="200"/>  <img src="files/ui_view_recipe.jpg" alt="View Recipe Screen" width="200"/>

Above are some screen captures from the application that give an idea on how the user interface is designed for this project. Navigation between the main activities is done from the Bottom Navigation bar as can be seen in the first three screenshots. Card views along with recycler views are used for the three main activities when generating the content of these activities. This includes recipe cards for the recipes screen, ingredient cards for the ingredients screen, and cookable recipes for the cook screen. These cards are fully swipeable (details of these actions can be read about in the user manual). Activities that go further into details from the three main activities, like the fourth screenshot which is viewing a recipe's details, utilitize the menu bar to hold actions that can be done. 

# Test Plan and Results

Link to Test Plan: [Test Plan](https://github.com/antonej12/kitchen-companion/blob/master/files/Senior%20Design%20Test%20Plan.pdf)


**Overall Test Plan**
The important aspects I wish to cover with this test plan is making sure the functionality
of all systems within the application are working as intended. This starts with making
sure the reading and writing of data for both the recipe system and integredient system
are working as they should be, allowing the user to make changes and see what is
being stored correctly. The aspects that combine these two systems will undergo
integration testing to make sure the interfaces between these two systems work
correctly. Additional testing will be conducted to make sure authentication and data
security are functional. User experience testing will also be conducted to get useful
feedback from potential users that will help make the application better. Finally, various
testing mechanisms offered by Google Firebase will be leveraged to retrieve additional
information regarding performance and usability among varying devices.

Test Results:

|Test Case|Execution Notes|Results|
|---|---|---|
|User Authentication Test 1|Inputs: Valid login credientials; Outputs: Successful login|PASS - Executed 3/19/21|
|User Authentication Test 2|Inputs: Invalid login credientials; Outputs: Unsuccessful login|PASS - Executed 3/19/21|
|Recipe Storage System Test 1|Inputs: Logged in user; Outputs: view showing correct recipe data for the user|PASS - Executed 3/19/21|
|Recipe Storage System Test 2|Inputs: Logged in user, new recipe data; Outputs: Database updates with new data, updated view showing new data|PASS - Executed 3/19/21|
|Ingredient Storage System Test 1|Inputs: Logged in user; Outputs: view showing correct ingredient data for the user|PASS - Executed 3/19/21|
|Ingredient Storage System Test 2|Inputs: Logged in user, new ingredient data; Outputs: Database updates with new data, updated view showing new data|PASS - Executed 3/19/21|
|Data Security Test 1|Inputs: Logged in user, action sequence that attempts to access other users data; Output: Failed ability to access data other than logged in user's own data|PASS - Executed 3/19/21|
|Recipe Retrieval Test 1|Inputs: Logged in user, recipe and ingredient data; Outputs: Successful retrieval of recipes based on input data|PASS - Executed 3/19/21|
|Barcode Scanning System Test 1|Inputs: Logged in user, item with a barcode; Outputs: Successful scanning of item, updates to database and views with the newly scanned item|PASS - Executed 3/20/21|
|Unit Library Integrity Test 1|Inputs: Isolated testing using various inputs spanning normal, abnormal, and boundary conditions; Outputs: Correct/expected functionality of the unit library|PASS - Executed 3/20/21|
|Cooking Activity System Test 1|Inputs: Logged in user; Outputs: Successful runthrough of cooking activity, updated values in database and views when cooking finishes|PASS - Executed 3/20/21|
|User Experience Satisfaction Test 1|Inputs: User usage of application (beta version used by a few people); Outputs: Feedback corresponding to user experience|PASS - Executed 3/20/21|
|Firebase Robo Test 1|Test leveraging Firebase Test Lab's Robo Test|Unattempted due to time constraints|
|Firebase Performance Test 1|Test leveraging Firebase's Performance Monitoring|Unattempted due to time constraints|

# User Manual

Link to full user manual: [User Manual](https://github.com/antonej12/kitchen-companion/blob/master/Project_Assignments/userdocs.md)

**FAQs**

1. How do I get started using Kitchen Companion?
	- You will need to sign up with an email and a password so Kitchen Companion can keep track of all your awesome recipes and ingredients! Click on the register button on the login screen to create your account. Don't worry, its a quick and easy process and we will never flood your inbox with useless emails!

2. The recipe I want to cook isn't showing up!
	- Be sure to make sure you have all the required ingredients for that recipe! As Kitchen Companion improves, we hope to be able to show you what you are missing, but for now keep a keen eye out and make sure you aren't missing anything. Sometimes ingredients have slight differences in names that might be the reason why you can't see your recipe as ready to cook. If all else fails, head over to the recipe you want to cook in the Recipe Book and click the "Cook" button in the top right menu to manually start the cooking activity for that recipe.

3. Do my units of measure need to match for Kitchen Companion to recognize that I have an ingredient for a recipe?
	- No! Kitchen Companion will do work behind the scenes converting all units of measure to see what ingredients you have. Store your ingredients however you prefer and write your recipes with whatever units of measure make sense, we will do the rest.

# Spring Presentation
[Spring Presentation Slide Deck](https://docs.google.com/presentation/d/16lV30k5VJPebfR9sPBIMGZbJqEP6NsKh34qQlwuhY2E/edit?usp=sharing)

[Spring Presentation Video](https://www.youtube.com/watch?v=ZzVQTz4BEVE)

# Expo Poster
[Poster Link](Project_Assignments/posterFinal.pdf)

# Assessments

## Fall Assessment

<p>For my senior design project, I will be creating a mobile application called "Kitchen Companion". This application is all about making cooking and the kitchen experience easier for its users. The main features that will make this happen are an inventory keeper of ingredients the user has available in their kitchen, and a recipe suggester that uses the ingredient inventory to let a user know what they can make based on what they have available. This application will give me the full experience of application development from start to finish, something I have learned a lot about during my academic and professional career. This project will also give me the opportunity to get some experience working in a mobile environment, which is something I haven't yet done. This project will be a great way for me to show everything I have learned during my time at the University of Cincinnati.</p>
<p>I have taken many courses during my time at UC that will be beneficial going forward with my senior design project. Classes like CS1021C(Computer Science I), CS2021(Python Programming), and EECE3093C(Software Engineering) have all given me experience with C++, Python, and Java programming languages respectively. The knowledge I have gained about each languages and the differences between them will be beneficial towards deciding what language is best suited for my project. EECE3093C(Software Engineering) has also given me a good understanding of looking at a project as a whole, and not just as individual files of code. I have gained a strong introduction to the world of databases through CS4092 (Database Design), which is going to be an important part of the inventory side of my application.</p>
<p>As for my co-op experience, I gained a lot of knowledge about software development and software engineering during my time as a software engineering co-op with KLH Engineers. I worked with my manager Michael Brun (Software Architect) and Cody Couch (Software Programmer) on the company's application focused on maximizing business process and engineering efficiencies, and gained a lot of experience on application programming. A lot of the work I did involved the hook up between the front-end and the back-end, and while doing so, had a lot of conversations about user interface with Tim Butcher (Lead Technology Designer) who was the go-to person for things about user interface. These experiences will be beneficial as I design and program my senior project, and I am confident that the things I have learned through my co-op experiences will make the process easier.</p>
<p>I am very excited to be pursuing the project that I am. When I took my first programming class in high school, I knew software and application development would be something I would love to make a career out of. As I began college, I was interested to see if any other subject mater within CS would become more interesting to me as I went through the curriculum and co-ops. As I reach my final year at UC, I have certainly gained experiences in other topic areas that I have enjoyed, but nothing has come close to the passion I have for software programming and development. This project will serve as a great medium for me to show how much I have learned this being here at UC and showcase where my passions within computer science lie.</p>

<p>One of the reasons I like my project idea a lot, is that it is an idea that has a lot of attainable goals along the way that I can use to measure my success. I can have a very baseline expectation that should be very attainable as a minimum viable product that will still be a significant effort, but yield a good project. My preliminary approach to designing this application would be an application that allows users to manually input their kitchen inventory, and match that inventory against user-inputted recipes to determine what the user can cook. I can then look at the application from a far more advanced view, and have the ability for a user to use their phone to scan product bar codes to take stock of their kitchen, and then automatically scrape recipes from across the web based on what is in their stock. The path between these two approaches yields many different milestones I can hit and use as a measure of success. The incremental nature of my project sets me up for a clear way to determine results and accomplishments.</p>

## Spring Assessment

Obviously, by working alone, my individual contribution to the project was the entire thing. I was able to build on and apply the skills I had mentioned in my self-assessment from the Fall. These included things like programming knowledge gained through various classes I have taken at UC like CS1021C (Computer Science I) and CS2021 (Python Programming). This also includes knowledge about the software development process from courses like EECE3093C (Software Engineering). I also applied a lot of what I learned as a Software Engineering Co-op at KLH Engineers by doing application programming and user interface design and implementation. Overall, I was able to make good use of things I have learned during my time at UC and was also able to build upon those skills by working on this senior design project.

For my project, I created an Android application based around cooking recipes and keeping track of what ingredients users have on-hand. This required many of the skills mentioned in the paragraph above, but also many new things that I have yet to experience much of. These included mobile development, database design, using cloud resources, and more. I got up to speed with Android development by going through a lot of free tutorials and courses on the subject, and did similar things to learn about using cloud resources. I worked with Google Firebase to host the application, store my data, and authenticate users. Overall, I would call the project a success. I was able to create a functional Android application that does what it set out to do. I personally believe I had great successes designing my NoSQL database on Firebase, developing a unit library to make working with various units of measure simple, and making the application as usuable as possible given the time and resources available. The hardest challenges would generally come from my lack of familiarity with some of the fields I worked with, especially because a lot of these technologies are very new and bleeding edge. This would make finding reference material difficult and I would often realize that the reference material I did find was already out-of-date despite being only months old. Adding a barcode scanning feature to my app also proved to be very troublesome, as I quickly learned how unstandardized UPC codes are, but I believe I was able to make a good effort in implementing that feature to the best of my ability.

# Summary of Hours
**First Semester**
| Task | Hours |
|------|------|
|Assignment #1: Professional Biography|1
|Assignment #2: Team Formation/Idea Brainstorming|4
|Assignment #3: Capstone Assessment|2
|Assignment #4: Design Diagrams|2
|Assignment #5: Task Lists|2
|Assignment #6: Effort Matrix/Milestones|3
|Assignment #7: Major Constraints|1
|Assignment #8: Fall Presentation|3
|Research front-end frameworks/development|4
|Kotlin Android Intro Course|2
|Research mobile back-end development|4
|Kotlin Koans|3
|Research database platforms|3
|Investigate cloud platforms for database deployment|2
|Investigate Google's Barcode API|3
|Investigate user account implementation strategies for Android Apps|4
|Research into search engine/database querying for recipe retrieval system|4
||Total: 47

**Second Semester**

| Date    | Activity                                                                                                     | Hours            |
| ------- | ------------------------------------------------------------------------------------------------------------ | ---------------- |
| 1/18/21 | Android Kotlin Codelabs for Interface Design                                                                 | 4                |
| 1/20/21 | Google Firebase - Learning Cloud Firestore/Realtime Database                                                 | 3                |
| 1/22/21 | Google Firebase - Cloud Firestore Research/Data Design;<br>Android Studio - Project Creation/Git Integration | 3                |
| 1/24/21 | Senior Design - Test Plan                                                                                    | 2                |
| 1/25/21 | Development - SignIn/Register Activities using Firebase Authentication                                       | 4                |
| 1/27/21 | Development - Unit library creation                                                                          | 3                |
| 1/29/21 | Development - Bottom Navigation Bar                                                                          | 4                |
| 2/01/21  | Development - Ingredient Stock progress                                                                      | 4                |
| 2/03/21  | Development - Ingredient Stock: Custom Object from Firestore Integration                                     | 3                |
| 2/05/21  | Development - Ingredient Stock: adding new ingredients, UI improvements                                      | 4                |
| 2/07/21  | Development - Ingredient Stock: Swiping features - Delete (Full) + Edit (Visuals only)                       | 2                |
| 2/08/21  | Development - Ingredient Stock: Swiping features - Edit; Item OnClick -> Edit                                | 2                |
| 2/09/21  | Senior Design - User Docs                                                                                    | 2                |
| 2/10/21 | Development - Recipe Book: Custom Object <- Firestore                                                        | 3                |
| 2/12/21 | Delevopment - Recipe Book: View Recipe Activity                                                              | 3                |
| 2/15/21 | Development - Recipe Book: Edit Recipe Activity                                                              | 4                |
| 2/17/21 | Development - Recipe Book: Edit Recipe Activity, Swipe events, delete/add                                    | 4                |
| 2/19/21 | Development - Recipe Book: Restructuring of "schema"                                                         | 2                |
| 2/22/21 | Senior Design - Slide Deck                                                                                   | 1                |
| 2/24/21 | Development - More "Schema" restructuring, unit storage overhaul                                             | 3                |
| 2/26/21 | Development - Schema restructuring reversals, ended up being a bad idea                                      | 2                |
| 3/01/21  | Development - Theory work on Querying cookable recipes, structure in place for displaying                    | 5                |
| 3/02/21  | Senior Design - Poster Rough Draft                                                                           | 1                |
| 3/03/21  | Development - Recipe Retrieval/Cook Fragment Display                                                         | 3                |
| 3/05/21  | Development - Cook Fragment, Cook Activity                                                                   | 3                |
| 3/08/21  | Development - Finished up Cook Activity, Barcode Scanner: Implementation                                     | 4                |
| 3/10/21 | Development - Barcode Scanner: Parsing progress                                                              | 2                |
| 3/12/21 | Development - Barcode Scanner: Parsing Complete                                                              | 4                |
| 3/15/21 | Development - Visual Updates/Design Changes                                                                  | 3                |
| 3/17/21 | Development - Visual Updates/Design Changes                                                                  | 4                |
| 3/19/21 | Testing - Importing Real data, App runthrough with real data                                                 | 3                |
| 3/20/21 | Testing - Bug Fixes from intial testing, Continue with more testing                                          | 3                |
| 3/22/21 | Senior Design - Document Updates: Poster, Design Diagram, Slide Deck, and User Docs                          | 4                |
| 3/24/21 | Senior Design - Record and Edit Video Presentation, Turn in all Materials to the sheets doc, peer reviews    | 4                |
| 4/19/21 | Senior Design - Final Report                                                                                 | 3                |
|         |                                                                                                              | Total Hours: 108 |

**Justification:** All acitivities completed in this time log were completed by Josh Antone. The dates weren't originally recored during the first semester, which was something I looked to do differently for the second semester. All first semester entries were either homework assignments or research. For the second semester, each entry is tagged with a category: Development is designated for any work related to programming the application, Senior Design is designated to homework assignments completed for the class, Testing is designated towards any testing activities, and any other tag is designated towards some form of self-learning. Development tags are supplemented with the area in which the development/programming was focused. These are typically focused on specific activities within the application.
