# Processing-Java Overview and Final Projects
Overview of Resources and High School Projects

What languages do we learn? (<a href="https://www.youtube.com/watch?v=bjFvcFjJpE0">
Video Explanation</a>)
- Processing-Java: manipulating visual based data, deploying to Android Devices
- Pure-Java with JDK, CMD, PowerShell, and Atom.io
- JavaScript with HTML, CSS, Chrome, and Atom.io

**Purpose**: illustrate the depth of the final projects and how lessons weave to produce modularity in Programming

Table of Contents
- Bibliography,
<a href="https://github.com/MercersKitchen/Processing-Java-Overview-and-Projects#bibliography">Click Here</a>
- Introductory Computer Science,
<a href="https://github.com/MercersKitchen/Processing-Java-Overview-and-Projects#introductory-computer-science-final-project-progression-version-of-final-exam-and-combined">Click Here</a>
- Intermediate Computer Science,
<a href="https://github.com/MercersKitchen/Processing-Java-Overview-and-Projects#intermediate-computer-science">Click Here</a>
- Advanced Computer Science (Includes Advanced Placement),
<a href="https://github.com/MercersKitchen/Processing-Java-Overview-and-Projects#advanced-computer-science">Click Here</a>

Other Notes to include, <a href="https://github.com/MercersKitchen/Processing-Java-Overview-and-Projects#to-include">Click Here</a>

---

Basic Information from Processing-IDE
- *Ensure following is included in IDE*
- File / Examples: Example Code organized by Basics, Topics, Demos, and from all installed libraries (for installed libraries, see BYOD)
- Sketch / Import Library / Add Library / Contribution Manager: Adding Examples like ...
  - Click the UPDATE Button for most current versions
  - Getting Started with Processing, 2nd Edition
  - Learning Processing, 2nd Edition
  - Processing for Android, 1st Edition
  - Processing Handbook, 2nd Edition
  - The Nature of Code

- Configuring the IDE: go to https://github.com/MercersKitchen/Device-Sideloading-Android

Final Projects will be hosted in GitHub using the Releases TAB
- Executable as a WINDOWS | Mac | Linux File
- Executable as an Android Side Load with associated driver specifics

---

# Introductory Computer Science Final Project Progression (version of final exam)
- See Introductory Computer Science for Lessons and Sequence of Projects

#### Common Outcomes
- Full Screen & Design Ratios
- Quit Button
- Side Loading to Android

#### Drawing Program - focus on mouse or touch screen interactions through lessons
- Review of entire course through a single project
- Note: students are able to suggest their own case study addressing following expectations

Purpose
- Learning Structural Modularity
- Introduction to Tabs in Processing-JAVA (to Introduce Procedural Programming)

Expectations
- 2D Shapes
- Images
- Interactivity like color changing effects
- Text
- Mouse Interactions like drawing
- Feature list that utilizes coding to mimic Paint.net, MS Paint, etc.

#### Music Program - focus on keyboard interactions and generalize to mouse or touch screen interactions

Purpose: Introduction to Adding Libraries through Processing-JAVA IDE and the code
- Adding music and sound effects

Expectations
- Buttons
  - Quit Button
  - Play-Pause
  - Stop
  - Forward, Reverse inside song (controlled by a variable and arrow keys)
  - Loop: once, defined number, infinite (controlled by a variable and arrow keys)
  - Next & Back Song Buttons with Introduction to Array Out of Bounds Error using IF
- Features
  - Meta Data: auto populating variables using music files
    - Able to use a IF-null catch to console-log which variables will show information

Advanced Features (Combinations of previous code)
- Auto playing: when current song finishes, automatically play the next song
- Music Organized into Folder accessed in code using pathways

---

# Intermediate Computer Science
- Using all expectations from Introductory Computer Science - manipulating visual and auditory data

#### Common Outcomes
- Full Screen & Design Ratios
- Quit Button
- Side Loading to Android

#### Weather Program - Auto Populating Variables from an API
- Review all Processing-Java from Introductory Computer Science
- Use an API (and all associated tools) to auto populate variables
- Introduce feedback based on ranges of variables that have been auto-populated
- Manipulating auto-populated variables to deliver specific information

#### Tic Tac Toe - Designing Algorithms to Play Tic Tac Toe
- Organizing increasing complexity in algorithms to facilitate workflow in programming
- Based on Google's Tic Tak Toe (2-player, easy, medium, impossible)

Purpose: introduction to Game (Situation) Simulation and evaluation of game space developing "whole game" understanding

Introduction to artificial intelligence (using high school leveled mathematics)
- Layering ways to make choices and hardcoding these choices to create levels
- Note: choices are made into procedures
- Extension: create randomly choose a percent and then use that percent to make a choice
  - "How can certain choices in game create other choices?"
  - "Why do some people with less experience in Tic Tak Toe win inconsistently? How do we program this?"

GUI Expectations
- Player keyboard (3 by 3)
- Scoreboard and record of games played (extension: fileIO with .txt)
- Reset button
- Dark Mode

Algorithm Procedures (illustration of translating game space into code)
- 2-person mode: click section, write, and alternate X & O
- Easy, medium, impossible modes: choice or hard coding of procedures below
- Recognize 3 in a row and stop the game: update scoreboard, activate reset, celebrate win
- Random Choice, response to X moves
- Recognize 2 in a row and block or complete 3 in a row
- Advanced: quit and save game state, to be restarted when game restarted

Note: order and coding of algorithmic procedures forms game rules, ethics, and morals

Exemplar Tic Tak Toe with Percentage Choices: https://github.com/QEHS-SpecialProjects/Tic-Tak-Toe-Dawson

Advanced Applications: Super Tic Tac Toe
- See Special Project: Super Tic Tak Toe in JavaScript, hosted locally

---

# Advanced Computer Science
- Pong Game (Visual Data): review Procedural Programming Methodology and Introduce Object Orientated Programming Methodologies
- Chatbot: Using Object Orientated Programming Methodologies for manipulating String Data (parsing, sorting, and searching)
- [Optional, non Advanced Placement] Password Program: manipulating String Data as one String Literal (password or passphrase)

Note: projects extend intermediate game rules, ethics, and morals to communication

#### Pong
- Uses Processing-Java: classes written in Pure Java, driver written in Processing-JAVA

Purpose: using visual data to learn new and abstract programming methodology (Object Orientated Programming)
- For example: a pong ball becomes an `object` automatically tracked by the computer, and might be instantiated infinitely

#### AP Labs: Chatbot
- Enrichment for Chatbot: Learning Responses based on past responses

CAUTION: Pure Java here directly uses JDK through CMD or PowerShell and a text editor like ATOM.io, Notepad++, or Visual Code
- Other options like IntelliJ, Eclipse, & Netbeans are possible

Purpose: using String Literals in Arrays and Lists (extension from visual data)

#### Password Program
- Password Generator

Password Generator
- Summary of Returned Values indicating weak, adequate, and strong passwords (or similar scale)
- Search of all passwords returning if it has been used before
- Indicator if Password seems like a password or a passphrase (using PascalCasing, i.e. classes, or camelCasing, i.e. procedures or variables, or snake_casing)
- Feature of Generating Random Passwords attending to
  - "Easy to Say": generating grade 1 reading vocabulary or list of questions using a seed formula
  - "Easy to Read": omitting characters that become confusing like S|5 or O|0 or 1|l|I|L|!|| (includes pipe as additional symbol)
  - Characters only: upperCase only and lowerCase only (using function to convert regardless of `Caps Lock`), limiting numbers and symbols
- Able to use NAN Error in Try-Catch as a decision loop

---

## Bibliography

*To Be Completed*

From Programming with Mosh
- The Complete Python Programming Course: http://bit.ly/35BLHHP
- The Ultimate Java Series: http://bit.ly/2tKoy8C
- The Ultimate Full-stack JavaScript Developer: http://bit.ly/2Ncpc5F
- JavaScript Basics for Beginners: http://bit.ly/2KZea52
- Python Tutorial for Beginners: https://youtu.be/_uQrJ0TkZlc
- Java Tutorial for Beginners: https://youtu.be/eIrMbAQSU34
- JavaScript Tutorial for Beginners: https://youtu.be/W6NZfCO5SIk
- Java Tutorial for Beginners [2019]: https://www.youtube.com/watch?v=eIrMbAQSU34&feature=youtu.be

https://www.educba.com/signup/

New Course: Data Structures and Algorithms Course
https://www.youtube.com/watch?v=XBoZPCgdnm8&feature=youtu.be&x=1


---

# To Include

Weather App (API)

Tick Tak Toe
- Goes with Super Tic Tac Toe
- Applications of algorithms using arrays

Pong (Introduction to OPP In Processing-JAVA)
- Night-Sky_Single
  - Review how constructor creates variables for rest of class and|or draw()
  - Algorithm for "Half off Screen", per ellipse (student generated algorithm, not included in GitHub)
- Night-Sky_Many

AP Labs
- Chatbot
  - Alternate: Password Program
    - Password Generator (see notes in `Advanced Computer Science / ReadMe.md`)

---
