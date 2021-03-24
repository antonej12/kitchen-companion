<h1>Kitchen Companion</h1>
Table of Contents:

- [Project Abstract](#project-abstract)
- [Project Description](#project-description)
- [User Stories and Design Diagrams](#user-stories-and-design-diagrams)
  - [User Stories](#user-stories)
  - [Design Diagrams](#design-diagrams)
  - [Design Diagram Descriptions](#design-diagrams-descriptions)
- [Project Tasks and Timeline](#project-tasks-and-timeline)
  - [Task List](#task-list)
  - [Timeline and Effort Matrix](#timeline-and-effort-matrix)
- [Fall Presentation](#fall-presentation)
- [Spring Presentation](#spring-presentation)
- [Self-Assessment Essay](#self-assessment-essay)
- [Professional Biography](#professional-biography)
- [Budget](#budget)
  - [Expenses](#expenses)
  - [Donations](#donations)
- [Appendix](#appendix)
  - [References](#references)
  - [Time Log](#time-log)

# Project Abstract
Choosing recipes to cook, specifically during a busy work week, can be hard and tiresome. Even if you have an idea of what you want to eat, you might find out that you are missing a key ingredient, making the process of choosing what to cook even more frustrating. 
Kitchen Companion is a mobile application that helps alleviate any stress when it comes to figuring out what to cook. It will allow users to keep track of what ingredients they have available and give them recipes to cook based on what they have. 
By using kitchen companion, users will spend less time trying to figure out what they can cook, and more time eating delicious meals.

**Team members**: Josh Antone (Computer Science) - antonejr@mail.uc.edu

**Faculty Advisor**: Dr. Fred Annexstein - annexfs@ucmail.uc.edu

# Project Description
Mobile app that provides user with features to make cooking food easier. The main functionality revolves around keeping stock of the user's ingredients, and giving them recipe suggestions based on what they have stocked.

# User Stories and Design Diagrams

## User Stories
 - As a **user**, I want to **add/remove grocery items from my kitchen inventory**, so that **I can keep my inventory up-to-date**
 - As a **user**, I want to **create/edit/delete recipes from a recipe list**, so that **I can keep track of things I like to cook.**
 - As a **user**, I want to **be given recipes based on my kitchen inventory**, so that **I can decide what to cook based on the ingredients I have.**
 
## Design Diagrams
- [View Design Diagrams](Project_Assignments/Design_Diagrams/design_diagrams.pdf)
 
## Design Diagram Descriptions
 
### D0
- Application user opens the android app using their phone. They use the application to update their kitchen stock, edit their recipe book, and find recipes based on the ingredients they have.

### D1
- Application user uses the android app to update their stock and recipe book.
- The information given by the user is stored in a database.
- The application receives information from the database when looking for recipes based on kitchen stock.
- The app displays the recipe information to the user through the phone's UI.

### D2
- Applications front-end receives input from the user and sends it to the back-end.
- The back-end processes the user information, turning into objects based on its purpose (kitchen stock or recipe information), and sends this information to the database.
- The database stores users' kitchen stock and recipe book information.
- When the user is requesting recipes based on kitchen stock, the database sends relevant information to the back-end.
- This information is processed and sent to the front-end where it is displayed to the user.

# Project Tasks and Timeline

## Task List
|Tasks  | Assigned to: |
|------|------|
|Research front-end frameworks/development to use for project| Josh Antone|
|Research mobile back-end development to use for project| Josh Antone|
|Research database platforms to use for project| Josh Antone|
|Research into search engines for figuring out how to retrieve recipes based on ingredients| Josh Antone|
|Design mobile user interface of the application| Josh Antone|
|Design search engine/algorithm for retrieving recipes based on ingredient stock| Josh Antone|
|Design database for storing ingredient stock and recipes| Josh Antone|
|Investigate Google's Barcode API for use with barcode scanning| Josh Antone|
|Investigate user account implementation for mobile apps| Josh Antone|
|Investigate cloud platforms for database deployment| Josh Antone|
|Develop the user interface for the mobile application| Josh Antone|
|Implement ingredient stock input feature| Josh Antone|
|Implement recipe input feature| Josh Antone|
|Implement database for storing ingredient stock and recipes| Josh Antone|
|Implement search engine/algorithm for recipe retrieval| Josh Antone|
|Test/Validate user interface properly works| Josh Antone|
|Test/Validate ingredient stock feature properly works| Josh Antone|
|Test/Validate recipe input feature properly works| Josh Antone|
|Test/Validate recipe retrieval feature properly works| Josh Antone|
|Refine ingredient stock feature to include barcode scanning of products| Josh Antone|
|Refine recipe input feature to include scrapping given URLs for recipes| Josh Antone|
|Refine recipe retrieval feature to also search the web for recipes instead of just the user's recipe database| Josh Antone|

## Timeline and Effort Matrix

|Tasks  | Assigned to: | Timeline | Effort Hours
|------|------|------|------|
|Research front-end frameworks/development to use for project| Josh Antone|10/19/20 - 10/25/20 |4
|Research mobile back-end development to use for project| Josh Antone|10/26/20 - 11/1/20|4
|Research database platforms to use for project| Josh Antone|11/2/20 - 11/8/20|3
|Research into search engines for figuring out how to retrieve recipes based on ingredients| Josh Antone|11/23/20 - 11/29/20|4
|Design mobile user interface of the application| Josh Antone|12/21/20 - 12/28/20| 3
|Design search engine/algorithm for retrieving recipes based on ingredient stock| Josh Antone|02/22/21 - 03/07/21|4
|Design database for storing ingredient stock and recipes| Josh Antone|01/11/21 - 01/24/21|4
|Investigate Google's Barcode API for use with barcode scanning| Josh Antone|11/16/20 - 11/22/20|3
|Investigate user account implementation for mobile apps| Josh Antone| 11/30/20 - 12/06/20|4
|Investigate cloud platforms for database deployment| Josh Antone|11/9/20 - 11/15/20|2
|Develop the user interface for the mobile application| Josh Antone| 12/21/20 - 12/28/20| 3
|Implement user account/login features| Josh Antone|12/28/20 - 01/10/21 | 6
|Implement ingredient stock input feature| Josh Antone|01/25/21 - 02/07/21|6
|Implement recipe input feature| Josh Antone|02/08/21 - 02/21/21|6
|Implement database for storing ingredient stock and recipes| Josh Antone|01/11/21 - 01/24/21|4
|Implement search engine/algorithm for recipe retrieval| Josh Antone|02/22/21 - 03/07/21|4
|Test/Validate user interface properly works| Josh Antone|03/08/21 - 04/04/21|4
|Test/Validate ingredient stock feature properly works| Josh Antone|03/08/21 - 04/04/21|4
|Test/Validate recipe input feature properly works| Josh Antone|03/08/21 - 04/04/21|4
|Test/Validate recipe retrieval feature properly works| Josh Antone|03/08/21 - 04/04/21|4
|Refine ingredient stock feature to include barcode scanning of products| Josh Antone|03/08/21 - 04/18/21|8
|Refine recipe input feature to include scrapping given URLs for recipes| Josh Antone|04/4/21 - Future|8
|Refine recipe retrieval feature to also search the web for recipes instead of just the user's recipe database| Josh Antone|04/4/21 - Future|8

# Fall Presentation
- [Youtube Video](https://www.youtube.com/watch?v=VRT8eZd8bXQ)
- [Google Slides](https://docs.google.com/presentation/d/1w_RPr58Pag0sL0Nmn0KoWPUVeOqIo8dhGb6HaEpxmc0/edit#slide=id.ga55225114d_1_3)

# Spring Presentation
- [Poster](https://github.com/antonej12/kitchen-companion/blob/master/Project_Assignments/posterFinal.pdf)
- [Youtube Video](https://www.youtube.com/watch?v=ZzVQTz4BEVE)
- [Google Slides](https://docs.google.com/presentation/d/16lV30k5VJPebfR9sPBIMGZbJqEP6NsKh34qQlwuhY2E/edit?usp=sharing)

# Self-Assessment Essay

<p>For my senior design project, I will be creating a mobile application called "Kitchen Companion". This application is all about making cooking and the kitchen experience easier for its users. The main features that will make this happen are an inventory keeper of ingredients the user has available in their kitchen, and a recipe suggester that uses the ingredient inventory to let a user know what they can make based on what they have available. This application will give me the full experience of application development from start to finish, something I have learned a lot about during my academic and professional career. This project will also give me the opportunity to get some experience working in a mobile environment, which is something I haven't yet done. This project will be a great way for me to show everything I have learned during my time at the University of Cincinnati.</p>

<p>I have taken many courses during my time at UC that will be beneficial going forward with my senior design project. Classes like CS1021C(Computer Science I), CS2021(Python Programming), and EECE3093C(Software Engineering) have all given me experience with C++, Python, and Java programming languages respectively. The knowledge I have gained about each languages and the differences between them will be beneficial towards deciding what language is best suited for my project. EECE3093C(Software Engineering) has also given me a good understanding of looking at a project as a whole, and not just as individual files of code. I have gained a strong introduction to the world of databases through CS4092 (Database Design), which is going to be an important part of the inventory side of my application.</p>

<p>As for my co-op experience, I gained a lot of knowledge about software development and software engineering during my time as a software engineering co-op with KLH Engineers. I worked with my manager Michael Brun (Software Architect) and Cody Couch (Software Programmer) on the company's application focused on maximizing business process and engineering efficiencies, and gained a lot of experience on application programming. A lot of the work I did involved the hook up between the front-end and the back-end, and while doing so, had a lot of conversations about user interface with Tim Butcher (Lead Technology Designer) who was the go-to person for things about user interface. These experiences will be beneficial as I design and program my senior project, and I am confident that the things I have learned through my co-op experiences will make the process easier.</p>

<p>I am very excited to be pursuing the project that I am. When I took my first programming class in high school, I knew software and application development would be something I would love to make a career out of. As I began college, I was interested to see if any other subject mater within CS would become more interesting to me as I went through the curriculum and co-ops. As I reach my final year at UC, I have certainly gained experiences in other topic areas that I have enjoyed, but nothing has come close to the passion I have for software programming and development. This project will serve as a great medium for me to show how much I have learned this being here at UC and showcase where my passions within computer science lie.</p>

<p>One of the reasons I like my project idea a lot, is that it is an idea that has a lot of attainable goals along the way that I can use to measure my success. I can have a very baseline expectation that should be very attainable as a minimum viable product that will still be a significant effort, but yield a good project. My preliminary approach to designing this application would be an application that allows users to manually input their kitchen inventory, and match that inventory against user-inputted recipes to determine what the user can cook. I can then look at the application from a far more advanced view, and have the ability for a user to use their phone to scan product bar codes to take stock of their kitchen, and then automatically scrape recipes from across the web based on what is in their stock. The path between these two approaches yields many different milestones I can hit and use as a measure of success. The incremental nature of my project sets me up for a clear way to determine results and accomplishments.</p>

# Professional Biography
Josh Antone - University of Cincinnat CEAS, Computer Science '21

Email: antonejr@mail.uc.edu

Phone: 513-442-6747

<h2>Co-op Work Experience</h2>

 - Software Engineer Co-op, KLH Engineers (Fall 2019)
	 - Supported the development team through testing, debugging, revising, and writing of software source code used for maximizing business process and engineering efficiencies as well as customer service and product quality.
	 - Worked primarily in Microsoft Visual studio writing VB.NET source code.
	 - Gained experience working with user interfaces, specifically winforms and WPF, and the connections between front-end and back-end.
 - IT Quality Assurance Co-op, Gulfstream Aerospace (Spring 2018)
	 - Assisted QA lead with executing testing activities within the development and implementation of the software development lifecycle.
	 - Gained experience from the testing perspective with regards to the software development cycle.
 - UC Covid-19 Experiential Explorations Program (Summer 2020) 
	 - Because of the cancellation of my co-op with KLH Engineers due to the Covid-19 pandemic, I completed an EEP experience for my final co-op.
	 - This included using "upskilling" opportunities to hit a certain number of hours of self-learning.
	 - This experience gave me a lot of freedom to pursue various technical skills, allowing me to strengthen areas I have had experience in, and to gain introductory experience in areas I have no prior experience with.
	 - I used my experience to dive much deeper into Python, which I already had a lot of experience with, and to learn new skills like Javascript, C#, Microsoft Azure to name a few.

<h2>Project Sought</h2>
Based on my co-op experience with KLH Engineers, I would enjoy projects that would put me in the software development/software engineering side of things. However, I also wouldn't mind being a part of a project that allows me to explore new/less familiar material like machine learning, web development, or data analysis.

<h2>Technical Skills</h2>
Python, Javascript, VB.NET, C++, Java, HTML/CSS, C#, SQL

# Budget

## Expenses
None to date.

## Dontations
None to date.

# Appendix

## References
- [Android Kotlin Intro Couse](https://developer.android.com/courses/pathways/android-basics-kotlin-one)
- [Kotlin Documentation for Android Development](https://kotlinlang.org/docs/reference/android-overview.html)
- [Kotlin Koans](https://play.kotlinlang.org/koans/overview)
- [Google Firebase Documentation](https://firebase.google.com/docs)
- [Google Firebase Pricing Information](https://firebase.google.com/pricing)
- [Android Documentation on User Data](https://developer.android.com/guide/user-data)
- [Google ML Kit Barcode Scanning Documentation](https://developers.google.com/ml-kit/vision/barcode-scanning/android)
- [Xamarin Documentation](https://dotnet.microsoft.com/apps/xamarin)



## Time Log
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
