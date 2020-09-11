# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from a `JSON` object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in Preprocessing, and JavaScript Basics.

> You have **three hours** to complete this challenge. Plan your time accordingly.

## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You are free to work with the full data set as a stretch goal.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. How would you describe acessibility on the web to someone new to programming?
    Web accessibility is the practice (or art, depending on your perspective) of creating functionality in websites that allows ALL USERS—regardless of their circumstances—a high quality experience. Ultimately, accessibility is the cornerstone of web equality. If a site is only developed for the de facto user, the outcome is that anyone on the web with limiting abilities (or even just custom preferences, a lot of the time) cannot reach (access) the material on this site. 
    When websites are developed to benefit EVERYONE and ANYONE, the result is a site that (first and foremost) serves clients with disabilities. However, an accessible site lends not only to niche circumstances but also to other groups who might have altered preferences (i.e., larger font-size, screen reader, slow connection, etc.) 

2. Talk about 3 different things you can do to ensure your website is accessible. 
    A.	Semantic HTML. Not only does semantic HTML allow anyone with hindered sight to navigate through a site with greater ease, it also improves the findability of said site. Screen readers and search engines will understand information about the structure of your site. (Also, semantic HTML is a huge uptick in code hygiene—every great programmer who knows what they're doing values this immensely.)
    B.	Colors!! A great number of people are colorblind (including myself!). Choosing colors that won't pair colors commonly difficult for colorblind people to see is a really easy way to make someone's experience better.
    C.	Responsive units. Responsive units allow for people who need a larger font, different screen size, etc. to interact with your website more easily. (Additionally, responsive units allow for easier development in reactive websites, so this is a must regardless!) 

3. How would you explain the concept of a variable to someone new to programming?
    A variable in programming is almost like placeholder that contains a piece of information. That information may be a number, a sentence, a name, a color, whatever. Variables allow programmers to change the assigned value depending on certain conditions.  

4. What is the purpose of using functions in code?
    Functions are like a set of instructions to the computer. They are used to create and carry out some specific task. Functions help avoid repetitive code (minimizing repeatability is everything). Additionally, functions allow for a logical structure of a program. 

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set Up

Follow these steps to set up your project:

- [x] Create a forked copy of this project.
- [x] Add your Team Lead as collaborator on Github.
- [x] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [x] Create a new branch: git checkout -b `<firstName-lastName>`.

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Add a viewport meta tag to the head of your index.html page.
* [ ] Add responsive breakpoints to your code for 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.

### Task 3: Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Website is responsive at multiple breakpoints and looks good in-between breakpoints because student is using responsive units of measurement where appropriate. Student is using most semantic HTML for each element on page and has included ARIA roles where applicable (More research may be required to impliment ARIA roles)  
* [ ] Student demonstrates and can explain a deep understanding of basic programming concepts, when walking Team Lead through the explaination of their code.
* [ ] Use advanced array methods (.map, .reduce, .filter) to refactor your MVP code (create an array of all artists born in the 1900s with .filter, for example) - do this seperate from your MVP tasks


## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete by merging the branch back into master
