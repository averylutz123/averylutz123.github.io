# Avery's ePortfolio

Welcome to Avery's ePortfolio. This ePortfolio contains three enhanced computer programs that I originally developed during my four years in Southern New Hampshire University's computer science program. These enhancements focus on exmeplifying my skills in software design and engineering, data structures and algorithms, and database management. Additionally, this ePortfolio contains an informal narrated code review and a professional self-assesment that discusses my experience in SNHU's computer science program and my artifact selections. Thank you for your time and I hope you enjoy my work.

## Table of Contents
1. Proffesional Self-Assesment
2. Informal Code Review
3. Artifact One: Software Design and Engineering
4. Artifact Two: Data Structures and Algorithms
5. Artifact Three: Databases
6. ePortfolio Closing Statements

## 1. Proffesional Self-Assesmenet

## 2. Informal Code Review.

In this informal code review, the three artifacts that were selected for enhancmet are examined and critiqued in terms of their current functionality, organization, and complexity. The code for each artifact is analyzed in detail in order to ensure that areas for improvement are highlighted. Then the planned enhancement for each program is discussed. This code review is approximately forty minutes in length. 
Please click the provided link to view: [Avery's Code Review](https://www.youtube.com/watch?v=6nJdgMT_BmY).

## 3. Artifact One: Software Design and Engineering

### Artifact Description
	The artifact that has been selected to represent skills in software design and engineering was derived from the final project that was created within IT-312: Software Development with C++.Net titled Final Project 7-1: Dice Game. Originally developed in February of 2022, this program showcases a fully functional text-based game named Left Center Right (LCR) in which users take turns “rolling the dice” to see who can obtain and maintain the greatest number of gameplay chips. In order for the program to achieve total functionality, ten unique methods were utilized to distinguish the different gameplay mechanics such as rolling the dice and passing the chips. Additionally, three classes were implemented to represent the program components that were associated with the player, dice options, and game features. Because the contents of the LCR game prior to the artifact’s enhancements were confined to the text dialog within the console output, the program ensured that any potential user input was accounted for so that the game could appropriately communicate no matter what the user entered.  
	
  While the LCR program was initially developed with the C++ programming language, the enhancement for this artifact focused on transferring the code into a Java mobile application. This transfer to a different language has enabled the program to become a more interesting and interactive gaming experience that is more consistent with professional computer science standards. Colorful imagery, interactive buttons, multiple screens with diverse layouts, and new dialog options were applied within the Java mobile application to improve user engagement and to increase the desire for participants to replay the game multiple times. Therefore, the transfer of the LCR program into a Java mobile application resulted in the utilization of innovative skills and the implementation of design solutions that ensured a higher quality product was delivered upon completion. 

### Artifact Justification 
	The LCR program was selected to represent artifact one within the capstone portfolio due to the potential that the original application possessed for becoming a genuine mobile game that could be uploaded to the app store and played by the general public. The original version of the program merely existed as text dialog within the C++ console output in which the users and the game would communicate through a basic exchange of information. However, since the logic and instructions for the game are quite simple to understand, the program was an ideal platform for showcasing exceptional enhancement skills during the reconstruction of the artifact into a comprehensive final product. Additionally, the utilization of methods to separate different gameplay mechanics within the original LCR program provided a solid foundation for creating different screens that users could navigate through within the mobile application. Similarly, it was clear that the utilization of widgets in the mobile application, such as buttons, would offer a more natural transition between the various gameplay mechanics as opposed to the pre-existing functionality of accepting the user’s input to progress forward. Therefore, the LCR program provided an excellent opportunity for demonstrating skills in software design and engineering. 

### Demonstrated Skills and Abilities
	Within the artifact one enhancement, the ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals was effectively demonstrated. The implementation of more robust and efficient controls can be seen in the removal of the three classes that existed within the original version of the program and the replacement of these classes with calls to the Android specific Intent class. The three original classes were removed due to the minimal impact they had on the program’s performance that resulted in needless repetition, wasted space, and redundant variable declarations. Calls to the Intent class to pass data between each Java activity within the mobile application not only provided easier readability of the code, but also minimized the steps required for each gameplay mechanic to obtain total functionality. 
 
	Another innovative feature that was implemented to minimize redundancy and to improve the efficiency of the program can be seen in the button widget that was incorporated into the CalculateRollsActivity.java file. Within this activity, an if-else statement is utilized to determine whether a user has enough chips (a value greater than zero in the point tracker array) to progress forward into the next activity. Then, a single button is displayed to indicate that the user may “roll” the dice or “skip turn” by setting the text of the button to the designated response in the corresponding if-else statement branch. Likewise, each branch has a corresponding call to the intent class that will send the user back to the score board so that the next player may begin their turn or allow the current player to progress forward and roll the dice. By utilizing this technique to advance the game forward, the number of required Java activities, widgets, and methods is minimized. Thus, industry-standard software designs were implemented into the program and the ability to utilize well-founded and innovative techniques, skills, and tools in computing practices was further demonstrated.
 
	The last significant indicator for exhibiting the ability to utilize well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals can be seen in the effective organization of loops and branches that ensure smooth iterations between array elements. These iterations show exceptional skills in array handling to test the user’s input and to test the qualifications of each player until a winner is declared. For example, the program successfully iterates through the point tracking array to correctly determine when a single player element has a value equal to the total value of in-game chips. Additionally, the point tracking array and players’ names array needed to be passed between activities in order to correctly track the names of each player during every round and the number of chips distributed between all participants. The culmination of these skills resulted in the development of a program that successfully demonstrates an exemplary understanding of software design and engineering. 

### Enhancements
1. Nine of the ten original methods that existed within the C++ version of the game were transferred to the Java programing language. These methods now exist in the form of new methods that spread throughout the entirety of the program or as individual Java activities. The politeQuestion method was not included within the enhancements of the artifact since users were no longer required to enter text dialog to progress forward and thus unexpected responses did not need to be accounted for. 
2. Ten new Java activities were created to represent the different screens users will navigate through.
3. Ten new xml files were created to provide a clean and organized layout for each screen the users will interact with.
4. Fourteen new drawable png files were imported into the program to be utilized as imagery.
5. The strings xml file was updated to include forty new string values that are called throughout the program.
6. A new functional component was created to read from an external text file to display text discussing the creation and purpose of the game titled “About.”
7. A new method was developed that displays three different images each time a player “rolls” and the method is called. An if-else statement is utilized to select from six drawable options or the default image is utilized. 
8. Scroll bars were implemented in five xml layout files so users can move up and down the screen when required to continue reading text that is not visible upon the activity start.
9. Ten buttons were implemented as a mechanism for users to progress further into the game.
10. A new feature was added that instructs players on the order in which they should be sitting so that the chip passes are accurate to their real-life seating arrangement. 
11. Removed program content, such as the three unnecessary classes, that resulted in redundancy, repetition, and inefficient.
12. Improved comments within the code to correctly describe the purpose of major segments. 
13. Ensured formatting throughout each activity and xml file was well-structured, consistent in style, and consistently formatted.
14. Ensured code was error free. 

### Objectives
	Throughout the enhancement of artifact one, all corresponding objectives that had been planned prior to development were fully met and the expectations of these objectives have been exceeded. Within artifact one, innovative skills and techniques for implementing design solutions and accomplishing goals are demonstrated in the logical breakdown of each activity into clear segments of functionality. None of the individual program activities or methods are needlessly complex or contain content that extends past their intended purposes. For example, the CalculateRollsActivity.java file strictly exists to determine the number of rolls allotted to each player and to display the computed value onto the screen for users to read. Determining which activities, or screens, should be incorporated into the project also required creative decision making as the original version of the program had no such need for this level of  organization since the contents of the program were only displayed in the console output. 

### Reflection 
	Throughout the process of enhancing the LCR artifact, I learned the importance of focusing on big picture concepts instead of only fixating on little details. While the entirety of the final program is in fact comprised of little details that each needed to obtain total functionality, trying to perfect a single feature before the majority of the project exists can take time away from forming a cohesive and uniform product. Therefore, I learned that breaking down the broad goals of the project into various tasks based on functionality allowed me to build the program up in layers. For example, when creating a new activity, the first thing that needed to be accomplished was laying out the basic framework for the necessary widgets within the xml file without thinking about details such as fonts, placement, or color. Then, each widget was linked to the necessary functional components within the java file in which new methods would be added in order of importance. Then, the last step is to make the entire activity look visually appealing on the screen by adjusting colors and importing pictures. In this enhancement I learned that the little details of the project are absolutely important, however, they provide few benefits when other sections of the program are inadvertently being overlooked. 
	
	The biggest challenge that I faced while developing this artifact was relearning how to work within Android Studio. My experience with the IDE is quite minimal since I had only ever created a handful of small mobile application during my time in CS-360 in December of 2021. In fact, I had not worked with Java in a meaningful way since that course had ended, so the initial days of working on the LCR program revolved around learning basic concepts such as placing widgets, linking xml and java file contents, and applying functionality to widgets within each activity. Even objectives that I typically excel in accomplishing, such as reading from external text files, seemed more complicated in the mobile application format since the contents of the xml file always had to be considered with every decision. However, despite this challenge, the completed application turned out to be an enjoyable and well-designed product.
	
	The feedback for this artifact with its original submission was to improve the manner in which I discuss the course outcomes within the narrative. Specifically, I originally mentioned that I met all objectives, but I needed to identify and articulate which outcomes I met within the enhancement. Therefore, I changed the formatting of my narrative to specifically discuss how the artifact was improved in terms of the main skill that was exhibited: using well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals. I created a clear header for this section of my narrative titled “Demonstrated Skills and Abilities,” and stated the skill at the beginning of the first paragraph. I also incorporated some of the indicators of success to ensure my accomplishments were more obvious. 



## 4. Artifact Two: Data Structures and Algorithms

## 5. Artifact Three: Databases

## 6. ePortfolio Closing Statements





For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/averylutz123/averylutz123.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
